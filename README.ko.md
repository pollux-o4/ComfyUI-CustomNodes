[English](README.md) · 한국어

# ComfyUI-CustomNodes

현재는 RemoteWorker 하나만 포함되어 있습니다. 다른 ComfyUI 커스텀 노드도 준비되는 대로 추가할 예정입니다.

각 프로젝트는 별도 저장소에서 관리하고, 여기에는 Git 서브모듈로 연결합니다.

| 프로젝트 | 기능 |
| --- | --- |
| [RemoteWorker](https://github.com/pollux-o4/RemoteWorker) | ComfyUI 런타임 사이의 conditioning 전달, 원격 인코딩 및 프롬프트 생성 |

## 모음 가져오기

```sh
git clone --recurse-submodules https://github.com/pollux-o4/ComfyUI-CustomNodes.git
```

이미 복제한 저장소에서는 다음 명령을 실행합니다.

```sh
git submodule update --init --recursive
```

## 개별 프로젝트 설치

RemoteWorker 설치:

```sh
cd /path/to/ComfyUI/custom_nodes
git clone https://github.com/pollux-o4/RemoteWorker.git
```

## 고정 버전 갱신

```sh
git submodule update --remote RemoteWorker
```

RemoteWorker의 `user` 브랜치를 가져옵니다. 업데이트를 확인한 뒤 서브모듈 포인터를 커밋합니다.
