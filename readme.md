<!-- <p align='center'>
    <img src='./docs/img3.png' alt='' width='800'/>
</p> -->

<details align='center'>
    <summary> ð· ç¹å»å±å¼å®æ´åè½æªå¾</summary>
    <br>
    <p align='center'>
    <img src='https://user-images.githubusercontent.com/50035229/224493411-085ba405-81cd-4972-b87b-74a2e811f23d.png' alt='è¯­é³å¯¹è¯' width='800'/>
    <img src='https://user-images.githubusercontent.com/50035229/223590381-ed38db74-39f3-4e77-bd3a-aaa54d679286.png' alt='è§è²æ®æ¼' width='800'/>
    <img src='https://user-images.githubusercontent.com/50035229/223590817-37a56eac-ab6e-4293-862a-de0988ac50b7.png' alt='æå­æå¾' width='800'/>
    <img src='https://user-images.githubusercontent.com/50035229/224531308-378a5bc3-2964-4e32-905f-8237dafc3f91.png' alt='å¾çåä½' width='800'/>
    <img src='https://user-images.githubusercontent.com/50035229/224531775-3f0e1e1b-a373-4774-a8f0-e120ccba6670.png' alt='å¸®å©èå' width='800'/>
    </p>

</details>

<br>

<p align='center'>
   é£ä¹¦ Ãï¼GPT-3.5 + DALLÂ·E + Whisperï¼
<br>
<br>
    ð Feishu OpenAI ð
</p>


## ð» æºå¨äººåè½

ð£ è¯­é³äº¤æµï¼ç´æ¥ä¸æºå¨äººçææ¬²è¨ ð§

ð¬ å¤è¯é¢å¯¹è¯ï¼æ¯æç§äººåç¾¤èå¤è¯é¢è®¨è®ºï¼é«æè¿è´¯

ð¼ ææ¬æå¾ï¼æ¯æææ¬æå¾åä»¥å¾æå¾

ð­ è§è²æ®æ¼ï¼æ¯æåºæ¯æ¨¡å¼ï¼å¢æ·»è®¨è®ºä¹è¶£ååæ

ð ä¸ä¸æä¿çï¼åå¤å¯¹è¯æ¡å³å¯ç»§ç»­åä¸è¯é¢è®¨è®º

â° èªå¨ç»æï¼è¶æ¶èªå¨ç»æå¯¹è¯ï¼æ¯ææ¸é¤è®¨è®ºåå²

ð å¯ææ¬å¡çï¼æ¯æå¯ææ¬å¡çåå¤ï¼ä¿¡æ¯æ´ä¸°å¯å¤å½©

ð äº¤äºå¼åé¦ï¼å³æ¶è·åæºå¨äººå¤çç»æ

ð åºæ¯é¢è®¾ï¼åç½®ä¸°å¯åºæ¯é¢è®¾ï¼æ¹ä¾¿ç¨æ·ç®¡çåºæ¯ ð§

ð åå²åæ¡£ï¼è½»æ¾åæ¡£åå²å¯¹è¯ï¼ç»§ç»­è¯é¢è®¨è®º ð§

ð ç®¡çåæ¨¡å¼ï¼åç½®ç®¡çåæ¨¡å¼ï¼ä½¿ç¨æ´å®å¨å¯é  ð§


## ð é¡¹ç®ç¹ç¹

- ð åºäº OpenAI-[gpt-3.5-turbo](https://platform.openai.com/account/api-keys) æ¥å£
- ð éè¿ larkï¼å° ChatGPT æ¥å¥[é£ä¹¦](https://open.feishu.cn/app)
- ð¥ æ¯æ[Serverless äºå½æ°](https://github.com/serverless-devs/serverless-devs)ã[æ¬å°ç¯å¢](https://dashboard.cpolar.com/login)ã[Docker](https://www.docker.com/)ã[äºè¿å¶å®è£å](https://github.com/Leizhenpeng/feishu-chatgpt/releases/)å¤ç§æ¸ éé¨ç½²
- ð åºäº[goCache](https://github.com/patrickmn/go-cache)åå­é®å¼å¯¹ç¼å­

## é¡¹ç®é¨ç½²

###### æå³é£ä¹¦çéç½®æä»¶è¯´æï¼**[â¡ï¸ ç¹å»æ¥ç](#è¯¦ç»éç½®æ­¥éª¤)**

<details>
    <summary>æ¬å°é¨ç½²</summary>
<br>

```bash
git clone git@github.com:Leizhenpeng/feishu-chatgpt.git
cd feishu-chatgpt/code
```

å¦æä½ çæå¡å¨æ²¡æå¬ç½ IPï¼å¯ä»¥ä½¿ç¨ååä»£ççæ¹å¼

é£ä¹¦çæå¡å¨å¨å½åå¯¹ ngrok çè®¿é®éåº¦å¾æ¢ï¼æä»¥æ¨èä½¿ç¨ä¸äºå½åçååä»£çæå¡å

- [cpolar](https://dashboard.cpolar.com/)
- [natapp](https://natapp.cn/)

```bash
# éç½®config.yaml
mv config.example.yaml config.yaml

//æµè¯é¨ç½²
go run main.go
cpolar http 9000

//æ­£å¼é¨ç½²
nohup cpolar http 9000 -log=stdout &

//æ¥çæå¡å¨ç¶æ
https://dashboard.cpolar.com/status

// ä¸çº¿æå¡
ps -ef | grep cpolar
kill -9 PID
```



<br>

</details>

<details>
    <summary>serverlessäºå½æ°(é¿éäºç­)é¨ç½²</summary>
<br>

```bash
git clone git@github.com:Leizhenpeng/feishu-chatgpt.git
cd feishu-chatgpt/code
```

å®è£[severless](https://docs.serverless-devs.com/serverless-devs/quick_start)å·¥å·

```bash
# éç½®config.yaml
mv config.example.yaml config.yaml
# å®è£severless cli
npm install @serverless-devs/s -g
```

å®è£å®æåï¼è¯·æ ¹æ®æ¨æ¬å°ç¯å¢ï¼æ ¹æ®ä¸é¢æç¨é¨ç½²`severless`

- æ¬å° `linux`/`mac os` ç¯å¢

1. ä¿®æ¹`s.yaml`ä¸­çé¨ç½²å°åºåé¨ç½²ç§é¥

```
edition: 1.0.0
name: feishuBot-chatGpt
access: "aliyun" #  ä¿®æ¹èªå®ä¹çç§é¥å«ç§°

vars: # å¨å±åé
region: "cn-hongkong" # ä¿®æ¹äºå½æ°æ³è¦é¨ç½²å°åº

```

2. ä¸é®é¨ç½²

```bash
cd ..
s deploy
```

- æ¬å°`windows`

1. é¦åæå¼æ¬å°`cmd`å½ä»¤æç¤ºç¬¦å·¥å·ï¼è¿è¡`go env`æ£æ¥ä½ çµèä¸ go ç¯å¢åéè®¾ç½®, ç¡®è®¤ä»¥ä¸åéåå¼

```cmd
set GO111MODULE=on
set GOARCH=amd64
set GOOS=linux
set CGO_ENABLED=0
```

å¦æå¼ä¸æ­£ç¡®ï¼æ¯å¦æ¨çµèä¸ä¸º`set GOOS=windows`, è¯·è¿è¡ä»¥ä¸å½ä»¤è®¾ç½®`GOOS`åéå¼

```cmd
go env -w GOOS=linux
```

2. ä¿®æ¹`s.yaml`ä¸­çé¨ç½²å°åºåé¨ç½²ç§é¥

```
edition: 1.0.0
name: feishuBot-chatGpt
access: "aliyun" #  ä¿®æ¹èªå®ä¹çç§é¥å«ç§°

vars: # å¨å±åé
  region: "cn-hongkong" #  ä¿®æ¹äºå½æ°æ³è¦é¨ç½²å°åº

```

3. ä¿®æ¹`s.yaml`ä¸­ç`pre-deploy`, å»é¤ç¬¬äºæ­¥`run`åé¢çç¯åéæ¹ç½®é¨å

```
  pre-deploy:
        - run: go mod tidy
          path: ./code
        - run: go build -o
            target/main main.go  # å é¤GO111MODULE=on GOOS=linux GOARCH=amd64 CGO_ENABLED=0
          path: ./code

```

4. ä¸é®é¨ç½²

```bash
cd ..
s deploy
```

æ´å¤è¯¦ç»ä»ç»ï¼åè[ä»é 1minï¼ç¨ Serverless é¨ç½²åºäº gin çé£ä¹¦æºå¨äºº](https://www.bilibili.com/video/BV1nW4y1378T/)
<br>

</details>

<details>
    <summary>dockeré¨ç½²</summary>
<br>

```bash
docker build -t feishu-chatgpt:latest .
docker run -d --name feishu-chatgpt -p 9000:9000 \
--env APP_ID=xxx \
--env APP_SECRET=xxx \
--env APP_ENCRYPT_KEY=xxx \
--env APP_VERIFICATION_TOKEN=xxx \
--env BOT_NAME=chatGpt \
--env OPENAI_KEY=sk-xxx \
feishu-chatgpt:latest
```

---

å°ç½ç®æå docker é¨ç½²

- docker å°å: https://hub.docker.com/r/leizhenpeng/feishu-chatgpt

```bash
docker run -d --restart=always --name feishu-chatgpt2 -p 9000:9000 -v /etc/localtime:/etc/localtim:ro  \
--env APP_ID=xxx \
--env APP_SECRET=xxx \
--env APP_ENCRYPT_KEY=xxx \
--env APP_VERIFICATION_TOKEN=xxx \
--env BOT_NAME=chatGpt \
--env OPENAI_KEY=sk-xxx \
dockerproxy.com/leizhenpeng/feishu-chatgpt:latest
```

äºä»¶åè°å°å: http://IP:9000/webhook/event
å¡çåè°å°å: http://IP:9000/webhook/card

æå®å¡«å¥é£ä¹¦åå°
<br>

</details>

<details>
    <summary>äºè¿å¶å®è£åé¨ç½²</summary>
<br>

1. è¿å¥[release é¡µé¢](https://github.com/adminlove520/chatGPT_feishu_v1.0.1/releases/) ä¸è½½å¯¹åºçå®è£å
2. è§£åå®è£å,ä¿®æ¹ config.example.yml ä¸­éç½®ä¿¡æ¯,å¦å­ä¸º config.yml
3. è¿è¡ç¨åºå¥å£æä»¶ `feishu-chatgpt`

äºä»¶åè°å°å: http://IP:9000/webhook/event
å¡çåè°å°å: http://IP:9000/webhook/card

</details>

## è¯¦ç»éç½®æ­¥éª¤

- è·å [OpenAI](https://platform.openai.com/account/api-keys) ç KEY
- åå»º [é£ä¹¦](https://open.feishu.cn/) æºå¨äºº
  1. åå¾[å¼åèå¹³å°](https://open.feishu.cn/app?lang=zh-CN)åå»ºåºç¨,å¹¶è·åå° APPID å Secret
  2. åå¾`åºç¨åè½-æºå¨äºº`, åå»ºæºå¨äºº
  3. ä» cpolar æè serverless è·å¾å¬ç½å°å,å¨é£ä¹¦æºå¨äººåå°ç `äºä»¶è®¢é` æ¿åå¡«åãä¾å¦ï¼
     - `http://xxxx.r6.cpolar.top`ä¸º cpolar æ´é²çå¬ç½å°å
     - `/webhook/event`ä¸ºç»ä¸çåºç¨è·¯ç±
     - æç»çåè°å°åä¸º `http://xxxx.r6.cpolar.top/webhook/event`
  4. å¨é£ä¹¦æºå¨äººåå°ç `æºå¨äºº` æ¿åï¼å¡«åæ¶æ¯å¡çè¯·æ±ç½åãä¾å¦ï¼
     - `http://xxxx.r6.cpolar.top`ä¸º cpolar æ´é²çå¬ç½å°å
     - `/webhook/card`ä¸ºç»ä¸çåºç¨è·¯ç±
     - æç»çæ¶æ¯å¡çè¯·æ±ç½åä¸º `http://xxxx.r6.cpolar.top/webhook/card`
  5. å¨äºä»¶è®¢éæ¿åï¼æç´¢ä¸ä¸ªè¯`æºå¨äººè¿ç¾¤`ã `æ¥æ¶æ¶æ¯`ã `æ¶æ¯å·²è¯»`, æä»ä»¬åé¢ææçæéå¨é¨å¾éã
  è¿å¥æéç®¡ççé¢ï¼æç´¢`å¾ç`, å¾é`è·åä¸ä¸ä¼ å¾çææä»¶èµæº`ã
  æç»ä¼æ·»å ä¸ååè°äºä»¶
     - im:resource(è·åä¸ä¸ä¼ å¾çææä»¶èµæº)
     - im:message
     - im:message.group_at_msg(è·åç¾¤ç»ä¸­æææ¶æ¯)
     - im:message.group_at_msg:readonly(æ¥æ¶ç¾¤èä¸­@æºå¨äººæ¶æ¯äºä»¶)
     - im:message.p2p_msg(è·åç¨æ·åç»æºå¨äººçåèæ¶æ¯)
     - im:message.p2p_msg:readonly(è¯»åç¨æ·åç»æºå¨äººçåèæ¶æ¯)
     - im:message:send_as_bot(è·åç¨æ·å¨ç¾¤ç»ä¸­@æºå¨äººçæ¶æ¯)
     - im:chat:readonly(è·åç¾¤ç»ä¿¡æ¯)
     - im:chat(è·åä¸æ´æ°ç¾¤ç»ä¿¡æ¯)
 

5. åå¸çæ¬ï¼ç­å¾ä¼ä¸ç®¡çåå®¡æ ¸éè¿


## æ´å¤äº¤æµ

æ¬¢è¿å å¥âä¸æ¹éä¾ å®å¨å®éªå®¤"ï¼wechat:Qianli_zhishui

éå°å¶ä»é®é¢ï¼å¯ä»¥å å¥é£ä¹¦ç¾¤æ²é~

<img src='./docs/talk.png' alt='' width='300'/>


<details>
    <summary>å¬ä¼å·</summary>
    <img width="400" src="./docs/wechat.jpg">
</details>
