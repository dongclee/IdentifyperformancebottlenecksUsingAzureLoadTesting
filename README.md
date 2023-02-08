안녕하세요…

이동철 입니다. 제가 또 하나의 그림책을 하나 만들어 보았습니다. ^-^

Azure 상에서 웹 어플리케이션을 배포할 때, 가장 고민하는 부분 중의 하나가 배포 前에 웹 어플리케이션의 부하테스트 일 것입니다. 최근에 Azure 상에서 웹 어플리케이션의 부하테스트를 제공하는 Azure Load Testing 서비스가 GA 되었습니다.

General Availability: Microsoft Azure Load Testing is now Generally Available (https://azure.microsoft.com/en-us/updates/general-availability-microsoft-azure-load-testing-is-now-generally-available/)

저는 원래 개발에는 완전 젬병인 사람인데,, 위 기능이 궁금해서 아래 자습서를 한 번 수행해 보았습니다.

Tutorial: Run a load test to identify performance bottlenecks in a web app (https://learn.microsoft.com/en-us/azure/load-testing/tutorial-identify-bottlenecks-azure-portal)

위 한글 자습서를 기반으로 제가 수행한 결과를 그대로 스크린샷을 추가해서 문서를 만들어 보았습니다. 기본적인 내용은 위 링크와 거의 동일하니,,, 이 점은 참고해서 제 문서를 봐 주세요,,,

본 문서에서 Azure Load Testing을 사용하여 부하테스트를 수행한 데모 환경은 아래와 같습니다.

 ![image](https://user-images.githubusercontent.com/42400574/217408771-2b7e7eb7-308c-4290-9880-268fb008d1b8.png)

본 문서에서는 Azure Cosmos DB 와 App Service를 기반으로 샘플 웹 어플리케이션을 배포했고, 실제 샘플 웹 어플리케이션의 성능 병목이 어느 부분에 있는지 확인하는 과정을 Azure Load Testing을 사용하여 진행합니다.

첨부 문서를 확인해 보시면 아시겠지만, Azure Load Testing을 통하여 Azure Cosmos DB의 초기 RU (Azure Cosmos DB 용량 단위) 를 너무 적게 설정해서 성능 병목이 있음을 확인합니다.

저 같은 개발에 젬병인 사람도 Azure Load Testing을 사용하여 손 쉽게 웹 어플리케이션의 부하테스트를 진행할 수 있을 것 같습니다.

감사합니다.



[Identify performance bottlenecks in a web app using Azure Load Testing.pdf](https://github.com/dongclee/IdentifyperformancebottlenecksUsingAzureLoadTesting/files/10680913/Identify.performance.bottlenecks.in.a.web.app.using.Azure.Load.Testing.pdf)


