---
title: "오시는 길"
bg: turquoise
color: white
fa-icon: map-marker
style: center
---
## 오시는 길

#### 지하철
지하철 3호선 / 6호선

약수역 9번 출구

약수역 사거리 카페베네 건물 5층

---

#### 버스

지선: 142, 144, 407번

간선: 6211, 7212번

---

#### 자동차
금호터널 방향에서 오실때

약수역 사거리에서 좌회전하면

KB국민은행과 카페베네 건물이 보입니다.
<br/>

<br/>
두건물을 사이에 끼고 우회전하셔서

10m 직진하시면

우측에 유료주차장이 있습니다.

(주차 1시간 무료)

**네비게이션에 '약수역 9번출구'로**

**검색해 주세요.**
<html>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <script src="../../docs/js/jquery-1.9.1.js"></script>
    <script type="text/javascript" src="../../docs/js/examples-base.js"></script>
    <script type="text/javascript" src="../../docs/js/highlight.min.js"></script>
    <script type="text/javascript" src="https://openapi.map.naver.com/openapi/v3/maps.js?clientId=IbVoT9BuB32w355RieYf&amp;submodules=panorama"></script>
    <link rel="stylesheet" type="text/css" href="../../docs/css/examples-base.css" />
</head>
<body>
<!-- @category Map -->
<div id="wrap" class="section">
    <div id="map" style="width:100%;height:300px;"></div>
    <code id="snippet" class="snippet"></code>
</div>
<script id="code">
//지도를 삽입할 HTML 엘리먼트 또는 HTML 엘리먼트의 id를 지정합니다.
var mapDiv = document.getElementById('map'); // 'map' 으로 선언해도 동일
//옵션 없이 지도 객체를 생성하면 서울시청을 중심으로 하는 11레벨의 지도가 생성됩니다.
var map = new naver.maps.Map(mapDiv);

var map = new naver.maps.Map('map', {
       scaleControl: false,
       logoControl: false,
       mapDataControl: false,
       zoomControl: true,
       minZoom: 1,
       center: new naver.maps.LatLng(37.5546007, 127.0101956),
       zoom: 15
   });
var marker = new naver.maps.Marker({
    position: new naver.maps.LatLng(37.5546007, 127.0101956),
    map: map
});
</script>
</body>
</html>
