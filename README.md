# java-document

자바관련 이것저것 잡다한거 넣어둔    

###### 내 개인적인 생각을 주절 거린거기에 다른 의견이 있을 수 있습니다.
###### 내가 뭐 정답도 아니고 엄청나게 잘 안다 하는것도 아닙니다~

면접을 보다보면 간혹 아주 원초적인 Java 관련 질문들을 받게 된다....   
예를들어 메모리의 구조라던가... GC의 변천사 각GC 별 작동 원리등 Foundation 관련 질문들이다.
음... 사실 이부분에 한해서는 JAVA를 처음 배울 시절 그러니까 지금으로 부터.. 약 10년 이상 전에 보고   
이 후 거의 신경을 쓰지 않은 부분이다.   
모르는 것이 아닌 뭐랄까... 논문으로 글로써 암기를 하고 남에게 전달을 해주기보다   
그냥 몸에 베여서 설계를 하거나 개발을 할때 당연스럽게 그런 부분을 고려하는 그런거 말이다...   

사실 조금은 그런생각도 했다.   
프레임워크를 만들거나, 특정 솔루션을 만들어 제품을 판매 하는 용도의 개발이 아니고서야   
특정 진형 (나의 경우는 Spring이 해당)의 프레임워크위에 작업을 하게 될 텐데....   
하며 저런 부분에 대해 크게 생각을 안했다.   
너무나도 좋은 오픈소스나 프레임워크들이 나오고 있다 보니 코어한 부분을 위주로 파서 해결 하기보다   
그 시간에 잘 버무려서 비지니스를 빠르게 만들어서 런칭 하는게 더 이득 아닌가 하는 생각이다.   

과거에는 장비의 가격도 비싸고 한번 리소스를 다 먹게 되면 장비를 내렸다 올리기도 리스크가 컸기에   
성능과 메모리등 자원을 신경을쓰는 설계를 많이 했었다.   
실제 나도 배치나 데몬등을 돌릴때 터미널을 열어 어플리케이션이   
구동되는동안 메모리의 변화나 IO의 변화를 계속 모니터링 하곤 했다.   
하지만 오늘날에는 일단 가격이 과거에 비해 싸지고,    
클라우드나 가상화 환경에서 서버를 돌리기에 Scale in.out이 매우 쉽다. 
JAVA의 특성상 GC가 메모리 관리를 해주기에 메모리 누수의 위험도 10년이상   
어플리케이션 개발을 JAVA로 하며 단 한번도 없었으니
정말 개념 없이 마구잡이로 자원을 끌어쓰지 않는한 크게 문제가 발생 하지 않을거라고 생각한다.   

주절주절 두서 없이 말을 썼는데 결국 어플리케이션 개발을 위해서는 대충 어떻게 돌아가는지   
그림과 개념정도만 알면 되지 않을까 하는 생각이다.   

그럼에도 이렇게 기록을 하게 된 계기는!   
면접시 종종 나오기도 하였고....   
나도 한번 다시 리마인드를 하며 공부를 하기 위해서 이다.
