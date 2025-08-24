# GET

## api

### [servertime](https://playentry.org/api/servertime)

* JSON String을 반환합니다
* 엔트리의 서버 시간을 [ISO 8601](https://namu.wiki/w/ISO%208601) 형식으로 반환합니다

### [autocomplete/suggest](https://playentry.org/api/autocomplete/suggest)

* JSON Array의 String을 반환합니다
* 엔트리에서 사용 된 태그를 자동완성합니다
* search값으로`query`를 받습니다

### [expansionBlock/ttsread.mp3](https://playentry.org/api/expansionBlock/tts/read.mp3)

* 올바른 데이터가 온 경우 mp3를, 잘못 된 데이터가 온 경우 JSON을 반환합니다
* 엔트리의 인공지능 블록 읽어주기 TTS 블록의 API입니다
* search 값으로 `text`,`speed`,`pitch`,`speaker`를 받습니다
* 허용하는 값

| speaker    | speed, pitch |
| ---------- | ------------ |
| kyuri      | -5 \~ 5      |
| jinho      |              |
| hana       |              |
| dinna      |              |
| brown      |              |
| minions    |              |
| sally      |              |
| nsabina    |              |
| nmammon    |              |
| nmeow      |              |
| nwoof      |              |
| clara      |              |
| matt       |              |
| shinji     |              |
| liangliang |              |
| meimei     |              |
| carmen     |              |
| jose       |              |

