---
description: 엔트리 그래프QL API
---

# POST

## 사용 방법

```javascript
fetch("https://playentry.org/graphql/", {
    headers: {
        "content-type": "application/json",
        "csrf-token": "",
        "x-token": "",
    },
    body: JSON.stringify({
        query: ``,
        variables: {},
    }),
    method: "POST",
});
```

Request Sample

```json
{
    "data": {
      "볼러오려던 값1": {
        },
      "볼러오려던 값2": {
        },

    },
    "extensions": {
        "runTime": "런타임 시간(ms, int)"
    }
}
```

***

## Banned 관련

### ipaddressBanned

```graphql
query {
    ipaddressBanned {
        bannedType
        ipaddress
        endDate
        reason
    }
}
```

* 입력 시 해당 ip가 밴 처리 된 ip인지 보여줍니다
* 반환 데이터 (예시)

```json
{
    "data": {
        "ipaddressBanned": {
            "bannedType": null,
            "ipaddress": null,
            "endDate": null,
            "reason": null
        }
    }
}
```

