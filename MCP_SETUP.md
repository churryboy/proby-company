# Stitch MCP 연동 설정

## 설정 완료

Stitch MCP 서버가 Cursor에 연동되었습니다.

## 설정 파일 위치

```
~/.cursor/mcp.json
```

## 설정 내용

```json
{
  "mcpServers": {
    "stitch": {
      "url": "https://stitch.googleapis.com/mcp",
      "headers": {
        "X-Goog-Api-Key": "AQ.Ab8RN6K9zPD5iDCtL0W4QrGTYuKkQbch0L_qy_PM1XUMLG4w-w"
      }
    }
  }
}
```

## 사용 방법

1. Cursor를 재시작하여 MCP 설정을 로드합니다.
2. MCP 서버가 활성화되면 Stitch 프로젝트 정보를 가져올 수 있습니다.
3. 프로젝트 ID와 스크린 ID를 사용하여 디자인 정보를 가져옵니다.

## Stitch 프로젝트 정보

- **프로젝트 ID**: 13667722179998136007
- **스크린 ID**: 56fee6bd80104ce4ba55f8a90db7b14b
- **스크린명**: Research Case Study Details

## 다음 단계

1. Cursor 재시작
2. MCP 서버 연결 확인
3. Stitch 프로젝트 데이터 가져오기
4. 이미지 및 코드 다운로드

