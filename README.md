## 스타트업 개발자 채용 大 박람회

(현재 준비중입니다.)

Seed ~ Series B에 있는 스타트업을 위한 채용정보 페이지입니다.  
Back-end, Frontend, Mobile 등 개발자를 대상으로 진행하고 있습니다.  
해당 스타트업에 종사하시는 분뿐만 아니라 채용 관련 정보를 알고 계시다면 PR을 해주세요!

## PR/스타트업 규칙

- Seed ~ Series B 이하인 Real 스타트업만 등록이 가능합니다. (Series C 이상 도달 시 채용 공고는 자동으로 삭제 처리될 수 있습니다.)
- [더브이씨](https://thevc.kr/SendBird)에 등록된 스타트업만 가능합니다.
- 회사 공식 or 서비스 웹페이지가 존재해야 합니다.
- 회사나 서비스 존재가 불확실하거나 명확하지 않은 경우, [잡플래닛](https://www.jobplanet.co.kr)에서 회사 점수가 낮다고 판단하는 경우, 가상화폐 거래, 대출, 보험, 금융 투자가 주 서비스로 확인되는 경우, 사람이 판단했을 때 이 회사는 좀 아니다 싶으면 PR이 거절될 수 있습니다.

## 스타트업 개발자 채용

<table>
    <tr>
        <th width="150">회사명</th>
        <th width="120">구분</th>
        <th width="120">마감일</th>
        <th width="120">최소경력</th>
        <th>링크</th>
    </tr>
    <tr>
        <td rowspan="1">반려생활 (SEED)
        </td>
        <td>프론트엔트</td>
        <td>
            2021-05-15
            </td>
        <td>무관</td>
        <td><a href="https://ban-life.com/recruit">링크</a></td>
    </tr>
    
</table>

## ${company_name}.json

jobs 폴더에 아래와 같이 json 파일을 생성하시면 됩니다.

```json
{
    "company": {
        "name": "반려생활",
        "link": "https://...", # 공식 홈페이지 주소
        "series_step": "ENUM(SEED|A|B)"
    },
    "recruits": [
        {
            "description": "OO 개발자를 모집합니다.",
            "category": "ENUM(FRONTEND|BACKEND|ANDROID|IOS)",
            "limit": "yyyy-MM-dd", # 마감일
            "link": "https://...",
            "minimum_career": "ENUM(ALL|NEW|YEAR1~10)",
            "minimum_qualifications": [
                "요구사항",
            ],
            "preferred_qualifications": [
                "우대사항",
            ]
        },
    ]
}
```
