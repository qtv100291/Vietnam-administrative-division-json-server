# Vietnam-administrative-division-json-server

> Instruction helps you create a fake API based on [json-server](https://github.com/typicode/json-server) to build the location selection functionality. Should only be used for educational purposes or project demo.\
> Hướng dẫn giúp bạn tạo nhanh một fake API dựa trên [json-server](https://github.com/typicode/json-server) để xây dựng chức năng lựa chọn địa điểm tại Việt Nam( Tỉnh/thành phố, quận/huyện, xã/phường ). Chỉ nên dùng cho mục đích học tập hoặc để demo dự án.

Data is periodically updated. Last update : 01/2025\
Data source: https://danhmuchanhchinh.gso.gov.vn/Default.aspx
<br/>

<div align="center"><img src='https://res.cloudinary.com/dqfemw7l4/image/upload/v1682758791/stuff/ezgif.com-video-to-gif_vlii0x.gif'></div>
<br/>

<b>Nếu thấy repository nhỏ này thật sự hữu ích với bạn, hãy nhấn vào nút Star để mình có thêm cố gắng update nó. Xin cảm ơn.</b>
<br>
( If you find this repository useful, please click star button to give me the motivation to keep this work up-to-date. Thanks so much )
<br>

## Demo

[Demo HTML - CSS - Javascript](https://codepen.io/qtv10291/pen/QWNxWer)
<br>
[Demo ReactJs](https://codepen.io/qtv10291/pen/gOdNgNo)

## Getting Started

1 . Clone this repository

```bash
git clone https://github.com/qtv100291/Vietnam-administrative-division-json-server.git
```

2 . Install dependencies

```bash
npm install
```

3 . Run JSON Server

```bash
json-server --watch db.json
```

Note : For deploying json-server to various free hosting, check this reference link:
https://github.com/jesperorb/json-server-heroku#deploy-json-server-to--free-hosting-site- (Heroku, Glitch, Azure) or https://github.com/kitloong/json-server-vercel (Vercel). If needed, using my json-server deployed: https://vietnam-administrative-division-json-server-swart.vercel.app <br>
( Ghi chú : Để deploy json-server lên một vài hosting miễn phí, các bạn có thể tham khảo link này: https://github.com/jesperorb/json-server-heroku#deploy-json-server-to--free-hosting-site- (Heroku, Glitch, Azure) hoặc https://github.com/kitloong/json-server-vercel (Vercel), hoặc nếu thấy cần, có thể dùng luôn api đã được mình đẩy lên: https://vietnam-administrative-division-json-server-swart.vercel.app )

## API List

- Get all City/Province : http://localhost:3000/province
- Get all District/Town of a City/Province : http://localhost:3000/district/?idProvince=${id of Province}
- Get all Ward/Commune of a District/Town : http://localhost:3000/commune/?idDistrict=${id of District}

Example : Get all District of Hanoi City ( id Province: 01 ) : http://localhost:3000/district/?idProvince=01
<br>
<br>

### Keywords

danh sách tỉnh thành việt nam json, api tỉnh thành phố quận huyện
