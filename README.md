# myReceipts 
AWS로 만드는 myReceipts 프로젝트 따라하기 설명서. 
myReceipts는 이메일로 발송 되는 카드결제 내역을 Google Spreadsheet로 수집하는 간단한 서비스입니다. 도메인 등록에서 부터, AWS에서 서비스 운영까지의 과정을 step-by-step로 설명합니다.

## 목차
1. AWS에서 도메인 등록과, 이메일 수신 하기 - Route 53, SES, S3
2. 결제내역 이메일과 Google Spreadsheet 준비하기
3. Google Spreadsheet로 API 연결하기
4. Lambda 함수로 이메일과 Sheet를 연결하기 - Lambda, Cloudwatch
5. 서비스 운영하기 