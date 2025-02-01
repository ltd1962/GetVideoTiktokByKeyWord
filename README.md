# GetVideoTiktokByKeyWord

### 1. How to use - Cách sử dụng

```
# Method GET: "https://ltdsoftware.online/apidowntik/keyword.php?key=" + keyword
# Example: "https://ltdsoftware.online/apidowntik/keyword.php?key=girlxinh"
```

### 2. Result - Kết quả trả về
# Success - Thành công
```
Example - Ví dụ
{
    {"code":0,"msg":"success","processed_time":0.7709,"data":{"videos":[{"video_id":"7243629694267018502","region":"VN","title":"\u0111\u00e3 nghi\u00ean c\u1ee9u ng\u1eafm g\u00e1i c\u00e0ng xinh s\u1ed1ng c\u00e0ng Th\u1ecd#TuHaoDaSac #girl #girls ","cover":"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/45da8c283ff948fda4c8ef57175d8068?biz_tag=musically_video.video_cover&lk3s=c1333099&nonce=87511&refresh_token=36e80fb19420ccbaf90332f6cf769419&shcp=-&shp=c1333099&x-expires=1738429200&x-signature=K02V1xoNXtgXsHTJBoxwrj70u3I%3D","ai_dynamic_cover":"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/db6596f2a4404fa3a8e9ff6087c2be8b_1686538973~tplv-tiktokx-origin.image?dr=1364&nonce=71096&refresh_token=0a5dc548d4e5e8f14c6cae626135eeb2&x-expires=1738494000&x-signature=19YESTVuppIJRzCPmYm0%2FgSh2zU%3D&biz_tag=tt_video&idc=maliva&ps=4f5296ae&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480","origin_cover":"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/97932c7cde3749c9b32004374277e084_1686538973~tplv-tiktokx-360p.image?dr=1363&nonce=22288&refresh_token=9d8952b3cab129951ff8f97fad7ad671&x-expires=1738494000&x-signature=t9hOzWb2f7gjAt48GoA%2BiJ%2BRZy4%3D&biz_tag=tt_video&idc=maliva&ps=d97f9a4f&s=SEARCH&sc=cover&shcp=c1333099&shp=d05b14bd&t=bacd0480","duration":9,"play":"https:\/\/v39-jp.tiktokcdn.com\/ff16b33ebcf6cf70aaf56c46c2cf4c5b\/679f5241\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/oY2pDOMhQqcRAQebkGosw88eEXBNJobFBqgWnW\/?a=1233&bti=NEBzNTY6QGo6OjZALnAjNDQuYCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=5776&bt=2888&cs=0&ds=6&ft=XsFbCqx4m-XPD12cNtKJ3wUfLD5KaeF~O5&mime_type=video_mp4&qs=0&rc=OThnZWk6ZTtoMzc8Zjc7aUBpam92dTo6Zmc7bDMzNzczM0BeMy8xXy02X2ExYy02YjAvYSMyay4ucjRnaTBgLS1kMTZzcw%3D%3D&vvpl=1&l=202502011108398CD4D32F93EE079FE8BA&btag=e000b5000","wmplay":"https:\/\/v39-jp.tiktokcdn.com\/ff16b33ebcf6cf70aaf56c46c2cf4c5b\/679f5241\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/oY2pDOMhQqcRAQebkGosw88eEXBNJobFBqgWnW\/? ...v....v....
}
```

# Fail - Thất bại
```
Example - Ví dụ
{
    "" hoặc {"code":-1,"msg":"'keywords' is required.","processed_time":0}
}
```
