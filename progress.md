# Progress

## 완료된 작업
- [x] GitHub Actions Node.js 20 deprecation 경고 해결을 위한 의존성 업데이트
  - `aws-actions/configure-aws-credentials` 버전을 `@v4` / `@v5` / `@v1` 에서 `@v6` (Node 24 지원)로 상향 조정
  - `delete-cdk-deploy.yaml` 내의 `actions/checkout@v3` 및 `actions/setup-node@v3` 버전을 `@v4`로 상향 조정
