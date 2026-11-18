# VIONA AI 1.5B — PocketPal용 GGUF

[GGUF 다운로드](https://github.com/soohun123/VIONA-ai-made-by-korean-student-GGUFfile/releases/download/viona-ai-1.5b-v1.0.0/VIONA-ai-1.5B-Q4_K_M.gguf) · [Releases](https://github.com/soohun123/VIONA-ai-made-by-korean-student-GGUFfile/releases/tag/viona-ai-1.5b-v1.0.0)

- 배포 이름: VIONA AI 1.5B
- 원본: Qwen2.5-Coder-1.5B-Instruct, Q4_K_M
- 파일: `VIONA-ai-1.5B-Q4_K_M.gguf`
- 크기: 1,117,320,768바이트 (약 1.12GB / 1.04GiB)
- SHA-256: `cc324af070c2ecbfd324a30884d2f951a7ff756aba85cb811a6ec436933bb046`
- 형식: GGUF v3, qwen2 아키텍처, 텐서 339개, 원본 컨텍스트 최대 32,768

## 무엇이 포함되나요?

이 파일은 VIONA 데스크톱에서 사용하는 Qwen 베이스 모델의 배포명입니다. 원본 GGUF와 SHA-256이 동일하며 모델 내부 메타데이터와 가중치는 변경하지 않았습니다. VIONA 추가 학습 LoRA, PC 앱의 도구·검색·코드 보완 기능, 이미지 생성기는 포함하지 않습니다. 별도 LoRA가 적용된 것처럼 표시하지 않습니다.

## PocketPal 사용법

1. 위 링크에서 GGUF 파일을 휴대폰에 다운로드하세요. GitHub의 Code → Download ZIP에는 모델이 들어 있지 않습니다.
2. PocketPal의 모델 화면에서 `+` → 로컬 파일 추가로 GGUF를 선택하세요. 버전에 따라 메뉴 이름이 다를 수 있습니다.
3. 모델을 로드하고 대화를 시작하세요. 모델에 포함된 Qwen 채팅 템플릿을 사용하세요.
4. 모바일에서는 컨텍스트 2,048부터 시작하고, 메모리 부족 시 컨텍스트·출력 길이를 낮추세요. 32,768은 원본 모델의 상한이며 모든 휴대폰에서 실행된다는 보장이 아닙니다.
5. 시스템 프롬프트를 설정할 수 있다면 `system-prompt-ko.txt`를 선택적으로 참고하세요. 프롬프트는 추가 학습이 아닙니다.

PC에서 GGUF 형식과 원본 해시를 검증했습니다. 실제 iPhone/PocketPal 앱 구동은 아직 테스트하지 않았습니다.

## 원본 및 라이선스

원본 제공: Qwen / Alibaba Cloud. 출처: https://huggingface.co/Qwen/Qwen2.5-Coder-1.5B-Instruct-GGUF
고정 리비전: `f86cb2c1fa58255f8052cc32aeede1b7482d4361`
원본 파일: `qwen2.5-coder-1.5b-instruct-q4_k_m.gguf`

모델은 원본 **Apache License 2.0**을 따릅니다. [LICENSE](LICENSE)를 함께 제공합니다. 별도 VIONA 앱 소스의 재배포 제한을 이 Qwen 모델에 적용하지 않습니다. VIONA는 배포 이름이며 Qwen 공식 배포 또는 제휴를 의미하지 않습니다.
