### xlsx_to_mysql

-----

* 대화형 선택상자로 1개 혹은 여러 개의 *.xlsx 파일을 선택한 뒤 병합 및 중복 제거하고
* MySQL DB로 각 Sheet를 Table화 하여 저장
* Select one or multiple *.xlsx files with the interactive selector, merge and remove duplicates
* Each sheet is converted into a table with MySQL DB and stored

-----

1. library 파일 속 db_config_example.py 파일에
사용할 MySQL DB에 해당하는 값을 넣고 db_config.py 라는 원래 이름으로 수정

2. 기존에 DB에 동일한 이름의 Table이 저장되어 있는경우 replace 해서 교체됩니다.

3. DB 상 재무제표에 기입된 금액 단위는 억원입니다.
