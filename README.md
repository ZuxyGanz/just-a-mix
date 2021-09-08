# just-a-mix
Nih image loli × cecan👍

### Case button
```bash
            case 'waifu':
            case 'loli':
            case 'husbu':
            case 'milf':
            case 'cosplay':
            case 'wallml':
            case 'aesthetic':
            case 'cecan':
            case 'uhkty':
            case 'shota':
            case 'nekonime':
            try {
            replyFakeLink(mess.wait)      
            let wipu = (await axios.get(`https://raw.githubusercontent.com/ZuxyGanz/just-a-mix/main/${command}.json`)).data
            let wipi = wipu[Math.floor(Math.random() * (wipu.length))]
            fs.writeFileSync(`./media/anime/${sender}.jpeg`, 
            await getBuffer(wipi))
            const aa = await ALDI.prepareMessage(from, fs.readFileSync(`./media/anime/${sender}.jpeg`), MessageType.image, {thumbnail: fakereply})
            const buttonsss = [{buttonId:`${prefix+command}`,buttonText: {displayText: '➡️ NEXT ➡️'}, type: 1}]
            const ButtonsMessages = {
            contentText: `Nih ${command} nya follow ig @zuxyganz_`,
            buttons: buttonsss,
            footerText: `Klik Next Untuk Melanjutkan Ke Gambar Berikutnya`,
            headerType: 4,
            imageMessage: aa.message.imageMessage
            }
            await ALDI.sendMessage(from, ButtonsMessages, MessageType.buttonsMessage, {quoted : mek})
            fs.unlinkSync(`./media/anime/${sender}.jpeg`)
            } catch {
            replyFakeLink(mess.error)  
            }    
            break
```

```bash
Khusus yang bisa ngoding ngap
Kalo ngga bisa nanti eror salahin Saia:v
```
