<div align="center">
  <h3 align="center">Baobab Infrastructure As Code</h3>

  <p align="center">
    바오밥 서비스의 인프라를 제공합니다. <br/> 
    현재 QA/Prod 환경은 Azure Kubernetes Service Cluster에서 실제로 배포하여 사용하고 있고, <br/> 
    Test 환경은 로컬 PC의 Minkube 환경에서 사용하고 있습니다. <br/> 
    해당 Repos에는 보안을 위해 미공개된 config-map들이 있습니다. <br/>
    따라서, 별도 작업이 필요하신 것이라면 iwantbaobab@gmail.com로 메일 부탁드립니다. <br/>
    내부 구성원의 경우 Slack 또는 Notion 확인 부탁드립니다. <br/>
    <br />
    <a href="https://github.com/baobab-kr/blog-service"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://baobab.blog">View Demo</a>
    ·
    <a href="https://github.com/baobab-kr/Infrastructure-as-Code/issues">Report Bug</a>
    ·
    <a href="https://github.com/baobab-kr/Infrastructure-as-Code/issues">Request Feature</a>
  </p>
</div>

## Environment

| Environment           | Explanation                                                                         |
| ------------------ | :-----------------------------------------------------------------------------------: |
| DEV           | 로컬 개발 환경(온-프레미스) 또는 로컬 개발 환경(도커 컴포즈, 도커 컨테이너)에서 개발 구성원들이 각자 간단한 단위 테스트를 수행하는 환경입니다.  |
| Test           |  Minikube 환경에서 인프라 담당자가 개발 시스템 테스트를 수행하는 환경입니다.  |
| QA          | 실제 AKS 환경에서 인프라 담당자와 개발 담당자가 함께 API 연동 등 통합 테스트를 수행하는 환경입니다.  |
| Prod           | 실제 사용자 환경에서 서비스를 사용하는 환경입니다.  |
