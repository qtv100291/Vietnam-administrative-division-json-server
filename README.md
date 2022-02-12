# Vietnam-administrative-division-json-server

> Instruction help you create a fake API based on [json-server](https://github.com/typicode/json-server) to build the location selection functionality. Should only be used for educational purposes or project demo.\
> Hướng dẫn giúp bạn tạo nhanh một fake API dựa trên [json-server](https://github.com/typicode/json-server) để xây dựng chức năng lựa chọn địa điểm tại Việt Nam( Tỉnh/thành phố, quận/huyện, xã/phường ). Chỉ nên dùng cho mục đích học tập hoặc để demo dự án.

Data is monthly updated. Last update : 11/2021\
Data source: https://danhmuchanhchinh.gso.gov.vn/Default.aspx

## Demo

<a href="https://codepen.io/qtv10291/pen/QWNxWer" target="_blank">https://codepen.io/qtv10291/pen/QWNxWer</a>

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
https://github.com/jesperorb/json-server-heroku#deploy-json-server-to--free-hosting-site-. If needed, using my json-server deployed: https://sheltered-anchorage-60344.herokuapp.com <br>
( Ghi chú : Để deploy json-server lên một vài hosting miễn phí, các bạn có thể tham khảo link này: https://github.com/jesperorb/json-server-heroku#deploy-json-server-to--free-hosting-site-, hoặc nếu thấy cần, có thể dùng luôn api đã được mình đẩy lên: https://sheltered-anchorage-60344.herokuapp.com )

## API List

- Get all City/Province : http://localhost:3000/province
- Get all District/Town of a City/Province : http://localhost:3000/district/?idProvince=${id of Province}
- Get all Ward/Commune of a District/Town : http://localhost:3000/commune/?idDistrict=${id of District}

Example : Get all District of Hanoi City ( id Province: 01 ) : http://localhost:3000/district/?idProvince=01

<b style="font-size:18px">If you find this repository useful, please click star button to give me the motivation to keep this work up-to-date :-< </b><br>
(Nếu thấy repository hữu ích, hãy nhấn vào nút Star để mình có thêm cố gắng update repo này :-< )
<br>

### Keywords

danh sách tỉnh thành việt nam json, api tỉnh thành phố quận huyện
