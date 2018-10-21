# Instruction

본 Jupyter Notebook에서는 Azure Machine Learning Studio Worskpace에 접근하기 위한 정보를 찾기 위해 settings.json 파일을 참조하고 있습니다. GitHub에 공개된 settings-orig.json과 settings-sample.json 파일을 참고하여 아래 작업을 하시면 됩니다.

1. settings-orig.json을 복사해서 settings.json 파일을 생성합니다.
2. Notebook에 설명된 대로 Azure Machine Learning Studio 화면으로 가서, workspace ID와 Authorization Token 값을 확인하여 이를 settings.json의 id, authorization_token 값에 넣습니다.
3. Notebook에 설명된 대로 API endpoint 값에는 Azure Machine Learning Studio Workspace를 생성한 지역에 따라 선택합니다. 예를 들면 Southeast Asia (동남아시아)라면 `https://asiasoutheast.studioapi.azureml.net` 를 입력합니다.

편리함을 위해 Gitignore에는 settings.json 파일은 동기화하지 않도록 하였습니다.

