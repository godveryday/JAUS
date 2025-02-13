
자율주행차량을 위한 개방형 아키텍처 기반의 통합 SW 플랫폼 및 복합지도 기반의 자율주행시스템 개발

위 내용 CHAPTER2 중
하지만 AUTOSAR 는 ADAS 와 같이 운전자를 보조하거나, 편의를 위한 서비스관점에서의 지능형자동차에 더 초점이 맞추어져 있으며, 다수의 지능형자동차뿐만 아니라 이종의 지능형시스템과의 연동에 대한 부분까지는 아직충분히 고려되고 있지 않다. 또한 제시하고 있는 방대한 규모의 표준 사양들을충족시킬 수 있는 소프트웨어 모듈 개발 및 통신 인터페이스 구성이 쉽지 않다는단점을 가지고 있다[106,113]. 그리고 표준사양을 만족하기 위해서 상용 BSW
모듈을 구매해야 하는 경우가 발생할 수 있으며, 이는 추가적인 비용 증가와상용 BSW 모듈을 사용하기 위한 설정 및 설계 복잡성이 단점으로 지적되고있다[113]. 따라서 AUTOSAR 기반의 자율주행차량은 현재의 자동차를 기반으로한 개발에는 유리할 수 있지만, 더 큰 관점으로 봤을 때, 이종의지능형시스템과의 연동 및 확장성에 있어서 자유롭지 못하며, 컴포넌트 개발에있어서 방대하고 복잡한 표준을 만족하는 것이 쉽지 않기 때문에 효율성이떨어진다고 판단된다. 반면에 JAUS 는 한대의 무인차량만을 대상으로 한 아키텍처가 아니라, 무인차량을 비롯해 무인차량의 운용에 필요한 지원시스템까지 포함하는무인시스템을 위한 아키텍처로 설계됐다. 또한, 다수의 무인시스템을 운용하는구조로, 각각의 시스템은 JAUS component 를 기반으로 한 모듈단위로 구성되고있다. 그리고 JAUS message 를 통해 상호운용성을 보장받을 수 있기 때문에시스템의 확장 및 소스 코드의 재사용이 가능하며, 표준 사양이 AUTOSAR 만큼복잡하지 않다는 장점을 가지고 있다. 마지막으로 자율주행 컴포넌트의알고리즘에 있어서 오픈 소스 시장이 활성화 되어 있으며, 자율주행을 위한최적화 된 계층 구조를 제시하고 있다. 

--- 

### 공식

잘 정리됌 = https://docs.openjaus.com/2024.0/jaus/basics/jaus_system/   (edge로 열기)

위 링크 보고 난 후, https://www.sto.nato.int/publications/STO%20Educational%20Notes/STO-EN-SCI-271/EN-SCI-271-02.pdf 보면 좋음

### 그 외 자료

https://archive.org/download/mipc-dsp_dla_mil/dsp.dla.mil_IEKX2LIRDTSKLYIOMB63KM2J7YE3RXWH.pdf

https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=cac145554c6e8e1d3a20c5542da5ae40c475b3e6


---

### 오픈소스

OpenJAUS SDK  , JAUS Tool Set (JTS)  , JAUS++  3가지 오픈소스 존재하는데

순서대로 지원 많음 , 보통, 필수기능만 지원

https://active-ist.sourceforge.net/jaus++.php --> 이해하기에 괜찮은 듯





---


### 정리

JAUS는 무인시스템을 위해 설계되었기때문에, 다음과 같은 서비스가 제공되어지는 것 같음

![image](https://github.com/user-attachments/assets/611c6356-39a3-4d34-8c44-9a00c68951ca)

서비스와 그에 맞는 메세지

위 7가지가 CORE SERVICE임

