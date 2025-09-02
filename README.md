# 🎯 Blog Study Certification DApp with DAO System

**블로그 공부 인증서 DApp - 리서치팀 & 개발팀으로 공부 목표 달성하고 NFT 인증서 받기! 🚀**

---

## ✨ 핵심 기능

### 🆓 무료로 인증서 만들기

- 블로그 URL만 입력하면 즉시 NFT 인증서 발급
- IPFS에 메타데이터 저장으로 영구 보관
- 공부한 내용을 블록체인에 영원히 기록

### 💰 돈 걸고 공부하기 (DAO 시스템)

- **🔍 리서치 팀**: 논문, 기술 조사, 트렌드 분석 (보증금: 0.01 ETH)
- **💻 개발 팀**: 코딩, 프로젝트 구현, 기술 개발 (보증금: 0.02 ETH)
- 목표 달성 시: 보증금 + 20% 보상 + 전문가 NFT 발급
- 목표 실패 시: 보증금이 팀 DAO 풀로 이동

---

## 🏆 전문가 NFT 등급 시스템

| 등급            | 조건      | 리서치 팀     | 개발 팀     |
| --------------- | --------- | ------------- | ----------- |
| 🥉 **브론즈**   | 1회 달성  | 리서치 입문자 | 개발 입문자 |
| 🥈 **실버**     | 3회 달성  | 리서치 분석가 | 개발자      |
| 🥇 **골드**     | 5회 달성  | 리서치 마스터 | 개발 마스터 |
| 💎 **플래티넘** | 10회 달성 | 리서치 전문가 | 개발 전문가 |

---

## 🛠️ 기술 스택

- **Frontend**: Next.js + TypeScript + Tailwind CSS + DaisyUI
- **Blockchain**: Hardhat + Solidity + OpenZeppelin Contracts
- **Storage**: IPFS (InterPlanetary File System)
- **Wallet**: RainbowKit + wagmi
- **Network**: Ethereum (Hardhat Local Network)

---

## 🌐 라이브 데모

**🚀 [Vercel에서 확인하기](https://blog-study-certification-dapp.vercel.app)** (배포 예정)

---

## 🚀 시작하기

### 1. 프로젝트 클론

```bash
git clone https://github.com/yelim8902/blog-study-certification-dapp.git
cd blog-study-certification-dapp/se-2-challenges/challenge-simple-nft-example
```

### 2. 의존성 설치

```bash
yarn install
```

### 3. 로컬 블록체인 실행

```bash
yarn chain
```

### 4. 스마트 컨트랙트 배포

```bash
yarn deploy
```

### 5. 프론트엔드 실행

```bash
yarn start
```

### 6. 브라우저에서 확인

- **메인 페이지**: http://localhost:3000
- **무료 인증서**: http://localhost:3000/myNFTs
- **DAO 시스템**: http://localhost:3000/dao
- **커뮤니티 검증**: http://localhost:3000/admin

---

## 🎮 사용 방법

### 무료 인증서 만들기

1. 지갑 연결 (MetaMask)
2. 블로그 URL 입력
3. 공부 주제 선택
4. 설명 작성
5. "인증서 만들기" 클릭
6. NFT 인증서 발급 완료! 🎉

### 돈 걸고 공부하기

1. **팀 선택**: 리서치 팀 또는 개발 팀
2. **정보 입력**: 사용자 이름, 블로그 URL, 설명
3. **보증금 예치**: 팀별 기본 보증금 자동 설정
4. **목표 설정**: 7일 내 블로그 포스팅 완료
5. **목표 달성**: 커뮤니티 검증 후 보상 + 전문가 NFT
6. **전문가 등급**: 완료 횟수에 따라 등급 상승

---

## 🏛️ DAO 시스템

### 그룹별 독립적인 보증금 풀

- **리서치 팀 DAO 풀**: 리서치 활동 보증금만 관리
- **개발 팀 DAO 풀**: 개발 활동 보증금만 관리
- **실시간 업데이트**: 보증금 입출금 시 해당 팀 풀만 업데이트

### 커뮤니티 검증

- 탈중앙화된 커뮤니티가 공정하게 검증
- 목표 달성 여부를 투표로 결정
- Web3의 핵심 가치인 "모두의 검증" 구현

---

## 📁 프로젝트 구조

```
se-2-challenges/challenge-simple-nft-example/
├── packages/
│   ├── hardhat/                 # 스마트 컨트랙트
│   │   ├── contracts/
│   │   │   ├── BlogStudyCertificate.sol  # NFT 컨트랙트
│   │   │   └── StudyDAO.sol              # DAO 컨트랙트
│   │   └── deploy/
│   └── nextjs/                  # 프론트엔드
│       ├── app/
│       │   ├── page.tsx         # 메인 페이지
│       │   ├── myNFTs/          # NFT 발급 페이지
│       │   ├── dao/             # DAO 시스템 페이지
│       │   └── admin/           # 커뮤니티 검증 페이지
│       └── utils/
│           └── simpleNFT/
│               └── nftsMetadata.ts  # NFT 메타데이터
```

---

## 🎯 프로젝트 특징

- **한국어 완전 지원**: 모든 UI가 한국어로 번역
- **친구들과 함께**: 사용자 이름으로 팀원 구분
- **시각적 피드백**: 그룹별 DAO 풀 실시간 표시
- **등급 시스템**: 브론즈부터 플래티넘까지 전문가 등급
- **데모 친화적**: 실제 블록체인 없이도 동작 확인 가능

---

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENCE.txt` 파일을 참조하세요.

---

## 👨‍💻 개발자

**yelim8902** - [GitHub](https://github.com/yelim8902)

---

## 🙏 감사의 말

- [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2) - 훌륭한 개발 프레임워크
- [OpenZeppelin](https://openzeppelin.com/) - 안전한 스마트 컨트랙트 라이브러리
- [IPFS](https://ipfs.io/) - 분산형 파일 저장소

---

**🎉 공부하자! 얘들아! 🎉**
