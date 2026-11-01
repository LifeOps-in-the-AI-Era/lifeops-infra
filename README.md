# LifeOps Infra

LifeOps in the AI Era의 인프라 설정 저장소입니다.

| 경로 | 용도 |
| --- | --- |
| `caddy/Caddyfile` | 정적 사이트 서빙 설정 |
| `smoke-test/index.html` | 정적 서빙 확인 |

## 설정 검증

```sh
LIFEOPS_WEB_ROOT=/path/to/site/dist caddy validate --config ./caddy/Caddyfile --adapter caddyfile
```
