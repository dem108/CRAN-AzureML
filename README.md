# AzureML

AzureML은 CRAN에서 관리되는 R 패키지로서, Azure Machine Learning Studio의 실험, 데이터셋, 웹서비스를 R을 통해 접근할 수 있게 도와줍니다. 

주요 기능 중에서 특히 임의의 R 함수를 웹서비스로 배포하는 기능을 살펴봅니다. 이때 R 함수는 아래와 같은 시나리오를 포함할 수 있습니다:

- 데이터가공
- 모델 적합 
- Inference

해당 웹서비스는 Azure라고 하는 Microsoft Cloud에서 관리됩니다. High Availability (서비스 지속성), Scalabilty (서버 확장성), 보안관리 등 핵심 기능이 기본 내장되어 있습니다.

서비스 배포가 되면 해당 휍서비스에 대한 API 설명서가 자동 생성됩니다.
