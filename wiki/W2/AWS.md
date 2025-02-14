## EC2
**AWS에서 제공하는 가상 서버**
- 인스턴스
	- 클라우드에서 사용하는 한 대의 **가상** 컴퓨터
### User-Data
인스턴스를 사용하는 사람이 정의한 초기 설정 데이터
- **EC2 User Data**는 서버 초기 설정을 자동화하는 강력한 도구
- 서버를 직접 설정할 필요 없이, 소프트웨어 설치와 서비스 구동을 자동화
**VS User-Data**(시스템이 관리하는 읽기 전용 데이터라고 이해)
- Instance Metadata 등
## ECR
1. **AWS의 완전관리형 Docker 이미지 레지스트리 서비스**
	1. Docker Hub와의 비교
		1. 보안 및 권한 관리
		2. 고가용성
2. Docker 이미지 레지스트리 서비스
	1. **Docker Hub**
		1. 공개/비공개 저장소
		2. 공식 이미지
		3. 자동 빌드 기능
	2. 애플리케이션을 컨테이너화한 이미지를 *공유*, *배포*, *버전 관리* 할 수 있다.
	3. 레지스트리 서비스가 없다면?
		1. 로컬에서 애플리케이션 개발 및 컨테이너 이미지 생성
		2. 클라우드 또는 외부 서버로 이미지 복사
		3. 서버 인스턴스에서 이미지 빌드 및 실행
		4. 자동화 어려움