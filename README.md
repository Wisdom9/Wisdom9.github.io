<!doctype html>
<html class="no-js" lang="zxx">

<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <title>Wisdom</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- CSS here -->
    
    
    
    
 <style>
     @import url("https://fonts.googleapis.com/css?family=Roboto:300,300i,400,500,500i,700,900&display=swap");
@import url("https://fonts.googleapis.com/css?family=Roboto:300,300i,400,500,500i,700,900&display=swap");
/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_extend.scss */
.flex-center-start {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: start;
  -ms-flex-pack: start;
  justify-content: start;
}

/* Normal desktop :1200px. */
/* Normal desktop :992px. */
/* Tablet desktop :768px. */
/* small mobile :320px. */
/* Large Mobile :480px. */
/* 1. Theme default css */
/* line 5, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
body {
  font-family: "Roboto", sans-serif;
  font-weight: normal;
  font-style: normal;
}

/* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.img {
  max-width: 100%;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

/* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
a,
.button {
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

/* line 20, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
a:focus,
.button:focus, button:focus {
  text-decoration: none;
  outline: none;
}

/* line 25, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
a:focus {
  text-decoration: none;
}

/* line 28, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
a:focus,
a:hover,
.portfolio-cat a:hover,
.footer -menu li a:hover {
  text-decoration: none;
}

/* line 34, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
a,
button {
  color: #1F1F1F;
  outline: medium none;
}

/* line 39, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
h1, h2, h3, h4, h5 {
  font-family: "Roboto", sans-serif;
  color: #001D38;
}

/* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
h1 a,
h2 a,
h3 a,
h4 a,
h5 a,
h6 a {
  color: inherit;
}

/* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
ul {
  margin: 0px;
  padding: 0px;
}

/* line 56, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
li {
  list-style: none;
}

/* line 59, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
p {
  font-size: 16px;
  font-weight: 300;
  line-height: 28px;
  color: #4D4D4D;
  margin-bottom: 13px;
  font-family: "Roboto", sans-serif;
}

/* line 68, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
label {
  color: #7e7e7e;
  cursor: pointer;
  font-size: 14px;
  font-weight: 400;
}

/* line 74, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
*::-moz-selection {
  background: #444;
  color: #fff;
  text-shadow: none;
}

/* line 79, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
::-moz-selection {
  background: #444;
  color: #fff;
  text-shadow: none;
}

/* line 84, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
::selection {
  background: #444;
  color: #fff;
  text-shadow: none;
}

/* line 89, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
*::-webkit-input-placeholder {
  color: #cccccc;
  font-size: 14px;
  opacity: 1;
}

/* line 94, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
*:-ms-input-placeholder {
  color: #cccccc;
  font-size: 14px;
  opacity: 1;
}

/* line 99, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
*::-ms-input-placeholder {
  color: #cccccc;
  font-size: 14px;
  opacity: 1;
}

/* line 104, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
*::placeholder {
  color: #cccccc;
  font-size: 14px;
  opacity: 1;
}

/* line 110, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
h3 {
  font-size: 24px;
}

/* line 114, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.mb-65 {
  margin-bottom: 67px;
}

/* line 118, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.black-bg {
  background: #020c26 !important;
}

/* line 122, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.white-bg {
  background: #ffffff;
}

/* line 125, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.gray-bg {
  background: #f5f5f5;
}

/* line 130, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.bg-img-1 {
  background-image: url(../img/slider/slider-img-1.jpg);
}

/* line 133, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.bg-img-2 {
  background-image: url(../img/background-img/bg-img-2.jpg);
}

/* line 136, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.cta-bg-1 {
  background-image: url(../img/background-img/bg-img-3.jpg);
}

/* line 141, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.overlay {
  position: relative;
  z-index: 0;
}

/* line 145, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.overlay::before {
  position: absolute;
  content: "";
  background-color: #001D38;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  opacity: .5;
}

/* line 157, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.overlay2 {
  position: relative;
  z-index: 0;
}

/* line 161, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.overlay2::before {
  position: absolute;
  content: "";
  background-color: #001D38;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  opacity: 0.6;
}

/* line 173, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.overlay_03 {
  position: relative;
  z-index: 0;
}

/* line 177, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.overlay_03::before {
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  background: #001D38;
  opacity: .6;
  content: '';
  z-index: -1;
}

/* line 190, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.bradcam_overlay {
  position: relative;
  z-index: 0;
}

/* line 194, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.bradcam_overlay::before {
  position: absolute;
  content: "";
  /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#5db2ff+0,7db9e8+100&1+24,0+96 */
  background: -moz-linear-gradient(left, #5db2ff 0%, #65b4f9 24%, rgba(124, 185, 233, 0) 96%, rgba(125, 185, 232, 0) 100%);
  /* FF3.6-15 */
  background: -webkit-linear-gradient(left, #5db2ff 0%, #65b4f9 24%, rgba(124, 185, 233, 0) 96%, rgba(125, 185, 232, 0) 100%);
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to right, #5db2ff 0%, #65b4f9 24%, rgba(124, 185, 233, 0) 96%, rgba(125, 185, 232, 0) 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#5db2ff', endColorstr='#007db9e8',GradientType=1 );
  /* IE6-9 */
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  opacity: 1;
}

/* line 210, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.section-padding {
  padding-top: 120px;
  padding-bottom: 120px;
}

/* line 214, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.pt-120 {
  padding-top: 120px;
}

/* button style */
/* line 220, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.owl-carousel .owl-nav div {
  background: transparent;
  height: 50px;
  left: 0px;
  position: absolute;
  text-align: center;
  top: 50%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
  -webkit-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  width: 50px;
  color: #707070;
  background-color: transparent;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%;
  left: 50px;
  font-size: 15px;
  line-height: 50px;
  border: 1px solid #4D6174;
  left: 150px;
  color: #fff;
}

/* line 248, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.owl-carousel .owl-nav div.owl-next {
  left: auto;
  right: 150px;
}

/* line 253, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.owl-carousel .owl-nav div.owl-next i {
  position: relative;
  right: 0;
}

/* line 260, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.owl-carousel .owl-nav div.owl-prev i {
  position: relative;
  top: 0px;
}

/* line 270, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.owl-carousel:hover .owl-nav div {
  opacity: 1;
  visibility: visible;
}

/* line 273, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.owl-carousel:hover .owl-nav div:hover {
  color: #fff;
  background: #FD8E5E;
  border: 1px solid transparent;
}

/* line 283, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.mb-20px {
  margin-bottom: 20px;
}

/* line 287, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.mb-55 {
  margin-bottom: 55px;
}

/* line 290, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.mb-40 {
  margin-bottom: 40px;
}

/* line 293, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.mb-20 {
  margin-bottom: 20px;
}

/* line 298, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/theme-default.scss */
.mb-50 {
  margin-bottom: 50px;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn {
  background: #fff;
  color: #131313;
  display: inline-block;
  padding: 18px 44px;
  font-family: "Roboto", sans-serif;
  font-size: 14px;
  font-weight: 400;
  border: 0;
  border: 1px solid #DB9A64;
  letter-spacing: 3px;
  text-align: center;
  color: #DB9A64 !important;
  text-transform: uppercase;
  cursor: pointer;
}

/* line 17, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn:hover {
  background: #DB9A64;
  color: #fff !important;
  border: 1px solid #DB9A64;
}

/* line 22, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn:focus {
  outline: none;
}

/* line 25, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn.large-width {
  width: 220px;
}

/* line 29, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3 {
  /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#DB9A64+0,fd8e5e+100 */
  background: #fdae5c;
  /* Old browsers */
  background: -moz-linear-gradient(left, #fdae5c 0%, #fd8e5e 100%);
  /* FF3.6-15 */
  background: -webkit-linear-gradient(left, #fdae5c 0%, #fd8e5e 100%);
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to right, #fdae5c 0%, #fd8e5e 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#DB9A64', endColorstr='#fd8e5e',GradientType=1 );
  /* IE6-9 */
  color: #fff;
  display: inline-block;
  padding: 19px 41px;
  font-family: "Roboto", sans-serif;
  font-size: 15px;
  font-weight: 500;
  border: 0;
  -webkit-border-radius: 30px;
  -moz-border-radius: 30px;
  border-radius: 30px;
  text-align: center;
  color: #fff !important;
  text-transform: capitalize;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
  cursor: pointer;
}

/* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3:hover {
  /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#DB9A64+0,fd8e5e+100 */
  background: #fdae5c;
  /* Old browsers */
  background: -moz-linear-gradient(left, #fdae5c 0%, #fd8e5e 100%);
  /* FF3.6-15 */
  background: -webkit-linear-gradient(left, #fdae5c 0%, #fd8e5e 100%);
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to right, #fdae5c 0%, #fd8e5e 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#DB9A64', endColorstr='#fd8e5e',GradientType=1 );
  /* IE6-9 */
  color: #fff !important;
}

/* line 62, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3:focus {
  outline: none;
}

/* line 65, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3.large-width {
  width: 220px;
}

/* line 70, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-white {
  color: #fff;
  display: inline-block;
  padding: 13px 27px;
  font-family: "Roboto", sans-serif;
  font-size: 14px;
  font-weight: 400;
  border: 0;
  border: 1px solid #fff;
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  border-radius: 5px;
  text-align: center;
  color: #fff !important;
  text-transform: capitalize;
  -webkit-transition: 0.5s;
  -moz-transition: 0.5s;
  -o-transition: 0.5s;
  transition: 0.5s;
  cursor: pointer;
  letter-spacing: 2px;
}

/* line 87, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-white:hover {
  background: #28AE61;
  color: #fff !important;
  border: 1px solid transparent;
}

/* line 92, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-white i {
  margin-right: 2px;
}

/* line 95, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-white:focus {
  outline: none;
}

/* line 98, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-white.large-width {
  width: 220px;
}

/* line 103, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-line {
  color: #DB9A64 !important;
  display: inline-block;
  padding: 17px 49px;
  font-family: "Roboto", sans-serif;
  font-size: 16px;
  font-weight: 500;
  border: 0;
  border: 1px solid #DB9A64;
  -webkit-border-radius: 0px;
  -moz-border-radius: 0px;
  border-radius: 0px;
  text-align: center;
  text-transform: capitalize;
  -webkit-transition: 0.5s;
  -moz-transition: 0.5s;
  -o-transition: 0.5s;
  transition: 0.5s;
  cursor: pointer;
}

/* line 118, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-line:hover {
  color: #fff !important;
  border: 1px solid transparent;
  background: #DB9A64;
}

/* line 123, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-line:focus {
  outline: none;
}

/* line 126, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn3-line.large-width {
  width: 220px;
}

/* line 130, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn2 {
  border: none;
  background: #DB9A64;
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  border-radius: 5px;
  color: #fff;
  font-size: 16px;
  font-weight: 600;
  display: inline-block;
  padding: 12px 36px;
  font-family: "Roboto", sans-serif;
  cursor: pointer;
}

/* line 143, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn2:hover {
  background: #DB9A64;
  color: #fff !important;
}

/* line 147, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.boxed-btn2:focus {
  outline: none;
}

/* line 151, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.line-button {
  color: #919191;
  font-size: 16px;
  font-weight: 400;
  display: inline-block;
  position: relative;
  padding-right: 5px;
  padding-bottom: 2px;
}

/* line 159, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.line-button::before {
  position: absolute;
  content: "";
  background: #919191;
  width: 100%;
  height: 1px;
  bottom: 0;
  left: 0;
}

/* line 168, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.line-button:hover {
  color: #009DFF;
}

/* line 171, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.line-button:hover::before {
  background: #009DFF;
}

/* line 175, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.book_now {
  display: inline-block;
  font-size: 14px;
  color: #009DFF;
  border: 1px solid #009DFF;
  text-transform: capitalize;
  padding: 10px 25px;
}

/* line 182, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_btn.scss */
.book_now:hover {
  background: #009DFF;
  color: #fff;
}

/* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
.section_title h3 {
  font-size: 36px;
  font-weight: 400;
  color: #fff;
  position: relative;
  z-index: 0;
  padding-bottom: 0px;
}

@media (max-width: 767px) {
  /* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
  .section_title h3 {
    font-size: 30px;
    line-height: 36px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
  .section_title h3 {
    font-size: 36px;
    line-height: 42px;
  }
}

@media (max-width: 767px) {
  /* line 18, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
  .section_title h3 br {
    display: none;
  }
}

/* line 24, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
.section_title p {
  font-size: 20px;
  color: #F91842;
  margin-bottom: 0;
  font-weight: 400;
  font-family: "Roboto", sans-serif;
  margin-bottom: 16px;
}

@media (max-width: 767px) {
  /* line 31, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
  .section_title p br {
    display: none;
  }
}

/* line 39, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
.section_title h4 {
  font-size: 22px;
  font-weight: 500;
  color: #001D38;
  padding-bottom: 21px;
}

/* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
.mb-60 {
  margin-bottom: 60px;
}

@media (max-width: 767px) {
  /* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
  .mb-60 {
    margin-bottom: 40px;
  }
}

/* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
.mb-60 {
  margin-bottom: 50px !important;
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
  .mb-60 {
    margin-bottom: 30px !important;
  }
}

@media (max-width: 767px) {
  /* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_section_title.scss */
  .mb-60 {
    margin-bottom: 20px !important;
  }
}

@media (max-width: 767px) {
  /* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
  .mobile_menu {
    position: absolute;
    right: 0px;
    width: 100%;
    z-index: 9;
  }
}

/* line 13, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_menu .slicknav_nav {
  background: #fff;
  float: right;
  margin-top: 0;
  padding: 0;
  width: 95%;
  padding: 0;
  border-radius: 0px;
  margin-top: 5px;
  position: absolute;
  left: 0;
  right: 0;
  margin: auto;
  top: 11px;
}

/* line 28, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_menu .slicknav_nav a:hover {
  background: transparent;
  color: #DB9A64;
}

/* line 32, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_menu .slicknav_nav a.active {
  color: #DB9A64;
}

@media (max-width: 767px) {
  /* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
  .slicknav_menu .slicknav_nav a i {
    display: none;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
  .slicknav_menu .slicknav_nav a i {
    display: none;
  }
}

/* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_menu .slicknav_nav .slicknav_btn {
  background-color: transparent;
  cursor: pointer;
  margin-bottom: 10px;
  margin-top: -40px;
  position: relative;
  z-index: 99;
  border: 1px solid #ddd;
  top: 3px;
  right: 5px;
  top: -36px;
}

/* line 55, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_menu .slicknav_nav .slicknav_btn .slicknav_icon {
  margin-right: 6px;
  margin-top: 3px;
  position: relative;
  padding-bottom: 3px;
  top: -11px;
  right: -5px;
}

@media (max-width: 767px) {
  /* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
  .slicknav_menu {
    margin-right: 0px;
  }
}

/* line 72, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_nav .slicknav_arrow {
  float: right;
  font-size: 22px;
  position: relative;
  top: -9px;
}

/* line 78, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_btn {
  background-color: transparent;
  cursor: pointer;
  margin-bottom: 10px;
  position: relative;
  z-index: 99;
  border: none;
  border-radius: 3px;
  top: 5px;
  padding: 5px;
  right: 5px;
  margin-top: -5px;
  top: -31px;
}

/* line 92, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slick-nav.scss */
.slicknav_btn {
  background-color: transparent;
  cursor: pointer;
  margin-bottom: 10px;
  position: relative;
  z-index: 99;
  border: none;
  border-radius: 3px;
  top: 5px;
  padding: 5px;
  right: 0;
  margin-top: -5px;
  top: -33px;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area {
  left: 0;
  right: 0;
  width: 100%;
  top: 0;
  z-index: 9;
  position: absolute;
}

@media (max-width: 767px) {
  /* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area {
    padding-top: 0;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area {
    padding-top: 0;
  }
}

/* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area {
  padding: 18px 0;
  background: #fff;
  background: transparent;
  padding: 25px 185px;
  padding: 25px 150px;
}

/* line 21, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area.details_nav_bg {
  background: #727272;
  padding-bottom: 0;
}

@media (max-width: 767px) {
  /* line 21, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area.details_nav_bg {
    padding-bottom: 10px;
  }
}

/* line 28, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area.details_nav {
  background: #001D38;
}

@media (max-width: 767px) {
  /* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area {
    padding: 10px 10px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area {
    padding: 10px 10px;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area {
    padding: 20px 20px;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  /* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area {
    padding: 20px 20px;
  }
}

/* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .logo-img {
  text-align: center;
}

@media (max-width: 767px) {
  /* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .logo-img {
    text-align: left;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .logo-img {
    text-align: left;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .logo-img {
    text-align: left;
  }
}

@media (max-width: 767px) {
  /* line 59, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .logo-img img {
    width: 70px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 59, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .logo-img img {
    width: 70px;
  }
}

/* line 71, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment {
  display: -webkit-box;
  display: -moz-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-align-items: center;
  -moz-align-items: center;
  -ms-align-items: center;
  align-items: center;
  -webkit-justify-content: flex-end;
  -moz-justify-content: flex-end;
  -ms-justify-content: flex-end;
  justify-content: flex-end;
  -ms-flex-pack: flex-end;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 75, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .Appointment .search_button {
    margin-right: 15px;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  /* line 75, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .Appointment .search_button {
    margin-right: 15px;
  }
}

/* line 84, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment .search_button a i {
  color: #E8E8E8;
}

/* line 91, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment .socail_links ul li {
  display: inline-block;
}

/* line 94, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment .socail_links ul li a {
  color: #A8A7A0;
  margin: 0 10px;
  font-size: 15px;
}

/* line 98, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment .socail_links ul li a:hover {
  color: #fff;
}

/* line 105, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment .book_btn {
  margin-left: 30px;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 105, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .Appointment .book_btn {
    margin-left: 0;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  /* line 105, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .Appointment .book_btn {
    margin-left: 0;
  }
}

/* line 113, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment .book_btn a {
  /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#DB9A64+0,fd8e5e+100 */
  background: transparent;
  font-family: "Roboto", sans-serif;
  padding: 14px 49px;
  font-size: 16px;
  font-weight: 600;
  border: 1px solid #DB9A64;
  color: #DB9A64;
  -webkit-border-radius: 0px;
  -moz-border-radius: 0px;
  border-radius: 0px;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 113, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .Appointment .book_btn a {
    padding: 12px 20px;
  }
}

/* line 126, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .Appointment .book_btn a:hover {
  /* Permalink - use to edit and share this gradient: https://colorzilla.com/gradient-editor/#DB9A64+0,fd8e5e+100 */
  background: #DB9A64;
  color: #fff;
}

/* line 134, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu {
  text-align: center;
  padding: 12px 0;
}

/* line 138, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li {
  display: inline-block;
  position: relative;
  margin: 0 10px;
}

/* line 148, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li a {
  color: #DB9A64;
  font-size: 16px;
  text-transform: capitalize;
  font-weight: 500;
  display: inline-block;
  padding: 0px 10px 0px 10px;
  font-family: "Roboto", sans-serif;
  position: relative;
  text-transform: capitalize;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 148, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .main-menu ul li a {
    padding: 0px 0px 0px 0px;
    font-size: 15px;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  /* line 148, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .main-menu ul li a {
    font-size: 15px;
    padding: 0px 0px 0px 0px;
  }
}

/* line 169, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li a i {
  font-size: 9px;
}

@media (max-width: 767px) {
  /* line 169, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .main-menu ul li a i {
    display: none !important;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 169, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area .main-menu ul li a i {
    display: none !important;
  }
}

/* line 200, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li a.active {
  color: #DB9A64;
}

/* line 202, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li a.active::before {
  opacity: 1;
  transform: scaleX(1);
}

/* line 207, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li a:hover {
  color: #DB9A64;
}

/* line 211, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li .submenu {
  position: absolute;
  left: 0;
  top: 160%;
  background: #fff;
  width: 200px;
  z-index: 2;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.02);
  opacity: 0;
  visibility: hidden;
  text-align: left;
  -webkit-transition: 0.6s;
  -moz-transition: 0.6s;
  -o-transition: 0.6s;
  transition: 0.6s;
}

/* line 223, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li .submenu li {
  display: block;
}

/* line 225, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li .submenu li a {
  padding: 10px 15px;
  position: inherit;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
  display: block;
  color: #000;
}

/* line 231, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li .submenu li a::before {
  display: none;
}

/* line 235, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li .submenu li:hover a {
  color: #000;
}

/* line 240, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li:hover > .submenu {
  opacity: 1;
  visibility: visible;
  top: 150%;
}

/* line 245, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li:hover > a::before {
  opacity: 1;
  transform: scaleX(1);
}

/* line 249, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area .main-menu ul li:first-child a {
  padding-left: 0;
}

/* line 255, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area.sticky {
  box-shadow: 0px 3px 16px 0px rgba(0, 0, 0, 0.1);
  position: fixed;
  width: 100%;
  top: -70px;
  left: 0;
  right: 0;
  z-index: 990;
  transform: translateY(70px);
  transition: transform 500ms ease, background 500ms ease;
  -webkit-transition: transform 500ms ease, background 500ms ease;
  box-shadow: 0px 3px 16px 0px rgba(0, 0, 0, 0.1);
  background: #311E25;
}

@media (max-width: 767px) {
  /* line 255, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .main-header-area.sticky {
    padding: 10px 10px;
  }
}

/* line 282, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area.sticky .main-menu {
  padding: 0;
}

/* line 285, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area.sticky .header_bottom_border {
  border-bottom: none;
}

/* line 288, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area.sticky .header_bottom_border.white_border {
  border-bottom: none !important;
}

/* line 294, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .main-header-area.sticky ul li a::before {
  position: absolute;
  content: "";
  background: #DB9A64;
  width: 100%;
  height: 3px;
  bottom: -33px;
  left: 0;
  opacity: 0;
  transform: scaleX(0);
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

/* line 312, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area {
  padding: 12px 0;
  background: #001D38;
}

@media (max-width: 767px) {
  /* line 315, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .header-top_area .social_media_links {
    text-align: center;
  }
}

/* line 319, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .social_media_links a {
  font-size: 15px;
  color: #C7C7C7;
  margin-right: 12px;
}

/* line 323, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .social_media_links a:hover {
  color: #DB9A64;
}

/* line 329, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .header_left p {
  color: #727272;
  font-weight: 400;
  font-size: 13px;
  margin-bottom: 0;
}

/* line 336, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .short_contact_list {
  text-align: right;
}

@media (max-width: 767px) {
  /* line 336, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .header-top_area .short_contact_list {
    text-align: center;
  }
}

/* line 342, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .short_contact_list ul li {
  display: inline-block;
}

/* line 344, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .short_contact_list ul li a {
  font-size: 13px;
  color: #919191;
  margin-right: 50px;
}

@media (max-width: 767px) {
  /* line 344, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .header-top_area .short_contact_list ul li a {
    margin-left: 0;
    margin: 0 5px;
  }
}

/* line 353, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .short_contact_list ul li a i {
  color: #DB9A64;
  margin-right: 7px;
}

/* line 361, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .header-top_area .header_right.d-flex {
  display: flex;
  justify-content: flex-end;
}

/* line 366, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
.header-area .search_btn i {
  color: #fff;
  font-size: 15px;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 370, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .search_btn {
    position: relative;
    right: 10px;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  /* line 370, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_header.scss */
  .header-area .search_btn {
    position: relative;
    right: 10px;
  }
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_bg_1 {
  background-image: url(../img/banner/banner.png);
}

/* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_bg_2 {
  background-image: url(../img/banner/banner_2.png);
}

/* line 7, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area {
  position: relative;
  z-index: 0;
}

/* line 17, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider {
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background-position: center center;
}

@media (max-width: 767px) {
  /* line 17, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider {
    height: auto;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 17, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider {
    height: 600px;
  }
}

/* line 27, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider .slider_text {
  padding: 303px 0;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 27, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text {
    padding: 130px 0;
  }
}

@media (max-width: 767px) {
  /* line 27, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text {
    padding: 130px 0;
  }
}

/* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider .slider_text.about_slide {
  padding: 241px 0 258px 0;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text.about_slide {
    padding: 130px 0;
  }
}

@media (max-width: 767px) {
  /* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text.about_slide {
    padding: 130px 0;
  }
}

/* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider .slider_text h3 {
  font-family: "Roboto", sans-serif;
  font-size: 80px;
  text-transform: capitalize;
  font-weight: 300;
  line-height: 90px;
  color: #fff;
  margin-bottom: 55px;
}

/* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider .slider_text h3 span {
  color: #DB9A64;
}

@media (max-width: 767px) {
  /* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text h3 {
    font-size: 30px;
    margin-bottom: 30px;
    line-height: 45px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text h3 {
    font-size: 54px;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text h3 {
    font-size: 70px;
  }
}

/* line 68, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider .slider_text p {
  font-size: 30px;
  font-weight: 400;
  color: #F91842;
  font-family: "Roboto", sans-serif;
  margin-bottom: 24px;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 68, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text p {
    font-size: 16px;
  }
}

@media (max-width: 767px) {
  /* line 68, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .slider_text p {
    font-size: 16px;
  }
}

/* line 84, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider .my_img {
  position: absolute;
  right: 0;
  bottom: 0;
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 84, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
  .slider_area .single_slider .my_img {
    width: 290px;
  }
}

/* line 91, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_slider.scss */
.slider_area .single_slider .my_img img {
  width: 100%;
}

/* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area {
  padding-bottom: 70px;
}

/* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area.plus_padding {
  padding-top: 100px;
}

@media (max-width: 767px) {
  /* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_info_area.plus_padding {
    padding-top: 30px;
  }
}

/* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area .about_text {
  margin-bottom: 30px;
}

/* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area .about_text h3 {
  font-size: 46px;
  font-weight: 300;
  color: #001D38;
}

@media (max-width: 767px) {
  /* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_info_area .about_text h3 {
    font-size: 30px;
  }
}

/* line 20, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area .about_text p {
  font-size: 15px;
  font-weight: 400;
  color: #727272;
  margin-bottom: 24px;
  margin-top: 10px;
}

/* line 27, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area .about_text a {
  padding: 13px 43px;
}

/* line 31, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area .about_thumb {
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
  overflow: hidden;
  margin-bottom: 30px;
}

/* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_info_area .about_thumb img {
  width: 100%;
}

/* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission {
  padding-top: 150px;
}

@media (max-width: 767px) {
  /* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission {
    padding-top: 50px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission {
    padding-top: 80px;
  }
}

/* line 51, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_thumb {
  position: relative;
  margin-bottom: 70px;
  padding: 30px 70px;
}

@media (max-width: 767px) {
  /* line 51, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission .about_thumb {
    padding: 30px;
  }
}

/* line 58, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_thumb img {
  width: 100%;
}

/* line 61, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_thumb .small_img_1 {
  width: 182px;
  height: 186px;
  position: absolute;
  top: 0;
  left: 0;
}

@media (max-width: 767px) {
  /* line 61, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission .about_thumb .small_img_1 {
    width: 100px;
    height: 100px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 61, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission .about_thumb .small_img_1 {
    width: 100px;
    height: 100px;
  }
}

/* line 75, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_thumb .small_img_1 img {
  width: 100%;
}

/* line 79, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_thumb .small_img_2 {
  width: 182px;
  height: 186px;
  position: absolute;
  bottom: 0;
  right: 0;
}

@media (max-width: 767px) {
  /* line 79, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission .about_thumb .small_img_2 {
    width: 100px;
    height: 100px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 79, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission .about_thumb .small_img_2 {
    width: 100px;
    height: 100px;
  }
}

/* line 93, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_thumb .small_img_2 img {
  width: 100%;
}

/* line 98, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_text {
  margin-bottom: 20px;
  padding-left: 68px;
}

@media (max-width: 767px) {
  /* line 98, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission .about_text {
    padding-left: 0;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 98, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
  .about_mission .about_text {
    padding-left: 0;
  }
}

/* line 107, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_text h4 {
  font-size: 42px;
  font-weight: 500;
  color: #001D38;
  margin-bottom: 15px;
}

/* line 113, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_about.scss */
.about_mission .about_text p {
  font-size: 16px;
  font-weight: 400;
  color: #4D4D4D;
  line-height: 28px;
  font-family: "Roboto", sans-serif;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.counter_area {
  padding-bottom: 30px;
  padding-top: 12px;
}

/* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.counter_area .single_counter {
  margin-bottom: 54px;
}

@media (max-width: 767px) {
  /* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
  .counter_area .single_counter {
    text-align: center;
  }
}

/* line 9, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.counter_area .single_counter h3 {
  color: #F91842;
  font-weight: 400;
  font-size: 70px;
  margin-bottom: 0;
  font-family: "Roboto", sans-serif;
  margin-bottom: 10px;
}

/* line 22, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.counter_area .single_counter p {
  color: #001D38;
  font-size: 16px;
  font-weight: 400;
  margin-bottom: 0;
  font-family: "Roboto", sans-serif;
}

/* line 30, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.counter_area .border_bottom {
  border-bottom: 1px solid #EAEAEA;
}

/* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details {
  background-image: url(../img/banner/home_details.png);
  background-size: cover;
  background-position: center center;
  padding: 140px 0;
}

@media (max-width: 767px) {
  /* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
  .home_details {
    padding: 80px 0;
  }
}

/* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .owl-carousel .owl-item img {
  display: inline-block;
  width: auto;
}

/* line 47, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .owl-carousel .owl-nav div {
  left: -147px;
  background: #DDDBD0;
  color: #001D38;
  border-color: transparent;
}

/* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .owl-carousel .owl-nav div.owl-next {
  left: auto;
  right: -147px;
}

/* line 57, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info {
  background: #fff;
  margin-top: 20px;
  padding: 50px 30px 30px 30px;
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
  position: relative;
}

/* line 65, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner span.for_sale {
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  border-radius: 5px;
  background: #FDAE5C;
  padding: 9px 21px;
  position: absolute;
  left: 0;
  top: 0;
  font-size: 15px;
  color: #fff;
  font-weight: 500;
  top: -20px;
  left: 34px;
}

/* line 78, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_header {
  border-bottom: 1px solid #E8E8E8;
  margin-bottom: 13px;
  padding-bottom: 29px;
}

/* line 82, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_header h3 {
  color: #001D38;
  font-size: 24px;
  font-weight: 500;
}

/* line 91, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_header .popular_pro span {
  color: #919191;
  font-size: 13px;
  font-weight: 400;
  display: inline-block;
  position: relative;
  top: 1px;
  margin-left: 5px;
}

/* line 103, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_content ul {
  margin-bottom: 20px;
}

/* line 105, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_content ul li {
  display: inline-block;
  margin-right: 41px;
}

@media (max-width: 767px) {
  /* line 105, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
  .home_details .modern_home_info .modern_home_info_inner .info_content ul li {
    margin-right: 7px;
  }
}

/* line 111, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_content ul li span {
  color: #001D38;
  font-size: 13px;
  font-weight: 400;
}

/* line 118, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_content p {
  font-size: 15px;
  line-height: 28px;
  color: #727272;
  margin-bottom: 0;
  margin-bottom: 13px;
}

/* line 126, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_content .prise_view_details span {
  color: #FF5748;
  font-size: 24px;
  font-weight: 500;
}

/* line 132, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_counter.scss */
.home_details .modern_home_info .modern_home_info_inner .info_content .prise_view_details a {
  padding: 7px 23px;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area {
  padding-top: 108px;
  padding-bottom: 83px;
}

/* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area.minus_padding {
  padding-top: 50px;
}

@media (max-width: 767px) {
  /* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
  .team_area {
    padding-top: 50px;
    padding-bottom: 50px;
  }
}

/* line 11, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team {
  margin-bottom: 30px;
}

/* line 13, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_thumb {
  overflow: hidden;
  margin-bottom: 26px;
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
  position: relative;
}

/* line 18, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_thumb img {
  width: 100%;
  -webkit-transform: scale(1);
  -moz-transform: scale(1);
  -ms-transform: scale(1);
  transform: scale(1);
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

/* line 23, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_thumb .social_link {
  position: absolute;
  bottom: 0;
  width: 100%;
  background: rgba(0, 29, 56, 0.5);
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
  text-align: center;
  padding: 13px 0;
  -webkit-transition: 0.5s;
  -moz-transition: 0.5s;
  -o-transition: 0.5s;
  transition: 0.5s;
  transform: translateY(100%) scale(1.2);
  opacity: 0;
  visibility: hidden;
}

/* line 35, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_thumb .social_link li {
  display: inline-block;
}

/* line 37, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_thumb .social_link li a {
  font-size: 15px;
  color: #C7C7C7;
  margin: 0 6px;
}

/* line 41, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_thumb .social_link li a:hover {
  color: #F91842;
}

/* line 49, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_info h3 {
  font-size: 22px;
  font-weight: 400;
  color: #001D38;
  margin-bottom: 0;
  font-family: "Roboto", sans-serif;
}

/* line 56, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team .team_info p {
  font-size: 14px;
  font-weight: 300;
  color: #727272;
  margin-top: 6px;
  margin-bottom: 8px;
  font-family: "Roboto", sans-serif;
}

/* line 68, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team:hover .team_thumb img {
  width: 100%;
  -webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  -ms-transform: scale(1.1);
  transform: scale(1.1);
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

/* line 73, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_team.scss */
.team_area .single_team:hover .team_thumb .social_link {
  transform: translateY(0%) scale(1);
  opacity: 1;
  visibility: visible;
}

/* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area {
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  position: relative;
  padding: 106px 0 120px 0;
  background: #3B2930;
  overflow: hidden;
}

@media (max-width: 767px) {
  /* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
  .testimonial_area {
    padding: 50px 0;
  }
}

/* line 15, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .single_testmonial p {
  color: #fff;
  font-weight: 400;
  font-size: 20px;
  line-height: 32px;
  margin: 34px 0;
  font-family: "Roboto", sans-serif;
}

@media (min-width: 320px) and (max-width: 1500px) {
  /* line 22, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
  .testimonial_area .single_testmonial p br {
    display: none;
  }
}

/* line 29, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .single_testmonial .author_name {
  position: relative;
  top: 4px;
  overflow: hidden;
  padding-left: 13px;
}

/* line 36, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .single_testmonial .testmonial_author .thumb {
  width: 68px;
  height: 68px;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%;
  float: left;
}

/* line 42, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .single_testmonial .testmonial_author h3 {
  color: #fff;
  font-size: 24px;
  font-weight: 400;
  margin-bottom: 5px;
  font-family: "Roboto", sans-serif;
  color: #DB9A64;
}

/* line 50, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .single_testmonial .testmonial_author span {
  font-size: 13px;
  font-weight: 400;
  color: #fff;
  font-family: "Roboto", sans-serif;
}

/* line 58, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .owl-carousel .owl-item {
  opacity: .4;
}

/* line 60, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .owl-carousel .owl-item.active {
  opacity: 1;
}

/* line 64, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .owl-carousel .owl-item img {
  display: inline-block;
  width: auto;
}

/* line 68, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .owl-carousel .owl-nav div.owl-next {
  left: auto;
  right: 0;
}

/* line 72, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .owl-carousel .owl-nav div {
  right: 57px;
  top: -28px;
  left: auto;
  width: 40px;
  height: 40px;
  line-height: 40px;
  border: 1px solid #7B5645;
  color: #7B5644 !important;
}

/* line 83, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .owl-carousel .owl-nav div:hover {
  background: #DB9A64;
  color: #fff !important;
}

/* line 88, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
.testimonial_area .owl-carousel .owl-stage-outer {
  position: relative;
  overflow: visible;
  -webkit-transform: translate3d(0, 0, 0);
}

@media (max-width: 767px) {
  /* line 88, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_testmonial.scss */
  .testimonial_area .owl-carousel .owl-stage-outer {
    overflow: hidden;
  }
}

/* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion button {
  font-size: 16px;
  color: #0f2137;
  font-weight: 500;
  font-weight: 500;
}

@media (max-width: 767px) {
  /* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
  #accordion button {
    font-size: 14px;
  }
}

/* line 11, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion .card {
  margin-bottom: 15px;
  border-radius: 0;
  border-radius: 0 !important;
  margin-bottom: 30px;
}

/* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion .card .card-header {
  background-color: transparent;
  padding: 4px 14px;
}

@media (max-width: 767px) {
  /* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
  #accordion .card .card-header {
    padding: 4px 0;
  }
}

/* line 23, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion .card .card-body {
  font-size: 16px;
  line-height: 28px;
  color: #888888;
  padding: 10px 30px 32px;
}

/* line 29, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion .card .collapse {
  border-bottom: 1px solid #d7dbe3;
}

/* line 31, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion .card .collapse.show {
  border-bottom: 1px solid transparent;
}

/* line 39, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion h5 {
  position: relative;
  z-index: 1;
}

/* line 65, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion h5 button.btn.btn-link:after {
  position: absolute;
  content: "\e648";
  top: 9px;
  right: 12px;
  height: auto;
  font-family: 'themify';
  color: #0f2137;
  font-size: 14px;
  left: -24px;
}

@media (max-width: 767px) {
  /* line 65, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
  #accordion h5 button.btn.btn-link:after {
    right: 10px;
  }
}

/* line 81, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion h5 button.btn.btn-link.collapsed:after {
  content: "\e64b";
  color: #0f2137;
  font-size: 14px;
}

/* line 88, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion h5 button i {
  height: 36px;
  width: 36px;
  font-size: 14px;
  display: inline-block;
  text-align: center;
  line-height: 36px;
  border-radius: 50%;
  margin-right: 20px;
  color: #fff;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

@media (max-width: 767px) {
  /* line 88, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
  #accordion h5 button i {
    display: none;
  }
}

/* line 104, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion h5 button.btn.btn-link.collapsed i {
  background: #f4f7f9;
  color: #0f2137;
}

@media (max-width: 767px) {
  /* line 104, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
  #accordion h5 button.btn.btn-link.collapsed i {
    display: none;
  }
}

/* line 116, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion .btn-link:hover {
  color: #182028;
  text-decoration: none;
}

/* line 120, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion.scss */
#accordion .btn {
  text-align: left !important;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area {
  padding-top: 100px;
  padding-bottom: 100px;
}

@media (max-width: 767px) {
  /* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
  .accordion_area {
    padding-top: 50px;
    padding-bottom: 50px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
  .accordion_area {
    padding-top: 60px;
    padding-bottom: 60px;
  }
}

/* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .accordion_thumb {
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
  overflow: hidden;
  padding-left: 68px;
}

@media (max-width: 767px) {
  /* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
  .accordion_area .accordion_thumb {
    padding-left: 0;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
  .accordion_area .accordion_thumb {
    padding-left: 0;
  }
}

/* line 22, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .accordion_thumb img {
  width: 100%;
  -webkit-border-radius: 10px;
  -moz-border-radius: 10px;
  border-radius: 10px;
}

/* line 28, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .faq_ask h3 {
  font-size: 46px;
  font-weight: 300;
  color: #001D38;
  margin-bottom: 57px;
}

@media (max-width: 767px) {
  /* line 28, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
  .accordion_area .faq_ask h3 {
    font-size: 38px;
    margin-bottom: 30px;
    margin-top: 20px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 28, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
  .accordion_area .faq_ask h3 {
    font-size: 38px;
    margin-bottom: 50px;
    margin-top: 20px;
  }
}

/* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .faq_ask #accordion .card {
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
  border: none;
  border-radius: .25rem;
  border-bottom: 1px solid #E8E8E8;
}

/* line 62, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .faq_ask #accordion .card .card-header {
  background-color: transparent;
  padding: 4px 14px;
  border: none;
}

/* line 67, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .faq_ask #accordion button {
  font-size: 15px;
  color: #001D38 !important;
  font-weight: 300 !important;
}

@media (max-width: 767px) {
  /* line 71, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
  .accordion_area .faq_ask #accordion button span {
    display: none;
  }
}

/* line 77, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .faq_ask #accordion .card .card-header {
  background-color: transparent;
  padding: 4px 30px;
}

/* line 91, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .faq_ask #accordion .card .card-body {
  font-size: 15px;
  line-height: 28px;
  color: #727272;
  padding: 10px 30px 32px;
  font-weight: 400;
  line-height: 28px;
}

/* line 101, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_accordion_area.scss */
.accordion_area .faq_ask #accordion .btn-link.focus, .accordion_area .faq_ask #accordion .btn-link:focus {
  text-decoration: none;
  border-color: transparent;
  box-shadow: none;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area {
  padding: 110px 0 90px 0;
  background: #311E25;
}

@media (max-width: 767px) {
  /* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
  .download_area {
    padding: 90px 0;
  }
}

/* line 8, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .download_text h3 {
  font-size: 36px;
  color: #fff;
  line-height: 46px;
  margin-bottom: 60px;
}

@media (max-width: 767px) {
  /* line 8, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
  .download_area .download_text h3 {
    font-size: 25px;
    color: #fff;
    line-height: 40px;
    margin-bottom: 20px;
  }
}

/* line 21, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .download_left {
  margin-bottom: 30px;
}

/* line 23, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .download_left p {
  font-size: 16px;
  line-height: 28px;
  color: #C9C9C9;
  margin: 20px 0;
}

/* line 29, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .download_left .boxed-btn3-line {
  margin-top: 28px;
}

/* line 34, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .progress_skills .single_progress {
  margin-bottom: 33px;
}

/* line 36, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .progress_skills .single_progress .label {
  margin-bottom: 16px;
}

/* line 38, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .progress_skills .single_progress .label span {
  font-size: 16px;
  color: #fff;
  font-weight: 400;
}

/* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .progress_skills .single_progress .progress {
  height: 6px;
  overflow: hidden;
  font-size: .75rem;
  background-color: #FFFFFF;
  border-radius: 5px;
}

/* line 50, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_download.scss */
.download_area .progress_skills .single_progress .progress .progress-bar {
  background: #DB9A64;
  border-radius: 5px;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area {
  background: #311E25;
}

/* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area .banner_img img {
  width: 100%;
}

/* line 8, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area .pos_up {
  position: relative;
  margin-top: -450px;
}

@media (max-width: 767px) {
  /* line 8, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
  .projects_details_area .pos_up {
    margin-top: -130px;
  }
}

/* line 15, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area .details_info {
  padding-bottom: 120px;
  padding-top: 60px;
}

@media (max-width: 767px) {
  /* line 15, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
  .projects_details_area .details_info {
    padding-top: 30px;
    padding-bottom: 60px;
  }
}

/* line 22, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area .details_info .single_details {
  margin-bottom: 63px;
}

@media (max-width: 767px) {
  /* line 22, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
  .projects_details_area .details_info .single_details {
    margin-bottom: 30px;
  }
}

/* line 27, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area .details_info .single_details h3 {
  font-size: 22px;
  font-weight: 400;
  color: #FFFFFF;
  margin-bottom: 29px;
}

/* line 33, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area .details_info .single_details p {
  color: #C9C9C9;
  font-size: 16px;
  line-height: 28px;
  margin-bottom: 30px;
}

/* line 41, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_products_details.scss */
.projects_details_area .details_info .button_link a {
  display: block;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_gallery.scss */
.gallery_area {
  background: #311E25;
  padding-top: 120px;
  padding-bottom: 120px;
}

/* line 7, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_gallery.scss */
.gallery_area .single_gallery .thumb img {
  width: 100%;
}

/* line 11, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_gallery.scss */
.gallery_area .single_gallery .gallery_heading {
  padding: 20px 0;
  margin-top: 7px;
  margin-bottom: 70px;
}

/* line 15, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_gallery.scss */
.gallery_area .single_gallery .gallery_heading span {
  color: #fff;
  font-size: 16px;
  font-weight: 400;
  display: block;
  margin-bottom: 7px;
}

/* line 22, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_gallery.scss */
.gallery_area .single_gallery .gallery_heading h4 {
  font-size: 24px;
  font-weight: 400;
  color: #DB9A64;
}

/* line 26, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_gallery.scss */
.gallery_area .single_gallery .gallery_heading h4:hover {
  text-decoration: underline;
}

/* line 33, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_gallery.scss */
.gallery_area .more_works a {
  display: block !important;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer {
  background-repeat: no-repeat;
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url(../img/banner/footer_bg.png);
}

/* line 7, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer p {
  font-family: "Roboto", sans-serif !important;
}

/* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top {
  padding-top: 145px;
  padding-bottom: 129px;
}

@media (max-width: 767px) {
  /* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
  .footer .footer_top {
    padding-top: 60px;
    padding-bottom: 30px;
  }
}

/* line 17, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .lets_talk {
  margin-bottom: 95px;
}

/* line 18, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .lets_talk h3 {
  font-size: 46px;
  margin-bottom: 20px;
  color: #fff;
}

@media (max-width: 767px) {
  /* line 18, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
  .footer .footer_top .lets_talk h3 {
    font-size: 28px;
    margin-bottom: 20px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 18, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
  .footer .footer_top .lets_talk h3 {
    font-size: 40px;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  /* line 18, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
  .footer .footer_top .lets_talk h3 {
    font-size: 38px;
  }
}

/* line 32, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .lets_talk h3 a {
  color: #DB9A64;
}

/* line 36, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .lets_talk p {
  font-size: 16px;
  line-height: 28px;
  color: #fff;
}

/* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .single_links {
  border: 1px solid #7A5444;
  padding: 25px 30px;
  cursor: pointer;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

@media (max-width: 767px) {
  /* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
  .footer .footer_top .single_links {
    margin-bottom: 10px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
  .footer .footer_top .single_links {
    padding: 25px 10px;
  }
}

/* line 54, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .single_links span {
  color: #fff;
  font-size: 24px;
  font-weight: 400;
}

/* line 59, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .single_links a {
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

/* line 61, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .single_links a i {
  color: #DB9A64;
  font-size: 20px;
}

/* line 66, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .single_links:hover {
  background: #CCAD85;
  border: 1px solid #CCAD85;
  color: #fff;
}

/* line 71, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .footer_top .single_links:hover a i {
  color: #fff;
}

/* line 78, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .copy-right_text {
  padding-bottom: 30px;
}

/* line 80, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .copy-right_text .copy_right {
  font-size: 14px;
  color: #919191;
  margin-bottom: 0;
  font-weight: 500;
}

@media (max-width: 767px) {
  /* line 80, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
  .footer .copy-right_text .copy_right {
    font-size: 13px;
  }
}

/* line 88, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_footer.scss */
.footer .copy-right_text .copy_right a {
  color: #DB9A64;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_bg_1 {
  background-image: url(../img/banner/bradcam.png);
}

/* line 4, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_bg_2 {
  background-image: url(../img/banner/bradcam2.png);
}

/* line 7, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_bg_3 {
  background-image: url(../img/banner/bradcam3.png);
}

/* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area {
  background-size: cover;
  background-position: center center;
  padding: 204px 0 193px 0;
  background-repeat: no-repeat;
  position: relative;
  z-index: 0;
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
  .bradcam_area {
    padding: 120px 0;
  }
}

@media (max-width: 767px) {
  /* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
  .bradcam_area {
    padding: 150px 0;
  }
}

/* line 27, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area.bradcam_area2 {
  height: 800px;
  padding-top: 231px;
  padding-bottom: 0;
}

@media (max-width: 767px) {
  /* line 27, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
  .bradcam_area.bradcam_area2 {
    padding-top: 131px;
    height: 400px;
    padding-bottom: 0;
  }
}

/* line 36, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area.bradcam_area2 h3 {
  font-size: 46px;
  font-weight: 400;
}

@media (max-width: 767px) {
  /* line 36, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
  .bradcam_area.bradcam_area2 h3 {
    font-size: 30px;
  }
}

/* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area h3 {
  font-size: 80px;
  color: #fff;
  font-weight: 300;
  margin-bottom: 0;
  text-transform: capitalize;
}

@media (max-width: 767px) {
  /* line 44, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
  .bradcam_area h3 {
    font-size: 30px;
  }
}

/* line 54, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area p {
  font-size: 18px;
  color: #fff;
  font-weight: 400;
  text-transform: capitalize;
}

/* line 59, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area p a {
  color: #fff;
}

/* line 61, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area p a:hover {
  color: #fff;
}

/* line 67, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area .icon {
  background: #FF5748;
  width: 136px;
  height: 136px;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%;
  text-align: center;
  line-height: 136px;
  margin: auto;
}

/* line 75, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area .icon i {
  color: #fff;
  font-size: 68px;
}

/* line 81, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area h4 {
  font-size: 70px;
  font-weight: 300;
  color: #fff;
  margin: 10px 0;
}

@media (max-width: 767px) {
  /* line 81, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
  .bradcam_area h4 {
    font-size: 40px;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 81, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
  .bradcam_area h4 {
    font-size: 40px;
  }
}

/* line 93, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_bradcam.scss */
.bradcam_area p {
  color: #fff;
  font-size: 16px;
  font-weight: 400;
  font-family: "Roboto", sans-serif;
}

/* line 3, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_tesmonial.scss */
.testmonial_area {
  padding-top: 0px;
  padding-bottom: 150px;
}

@media (max-width: 767px) {
  /* line 3, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_tesmonial.scss */
  .testmonial_area {
    padding-bottom: 50px;
  }
}

/* line 12, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_tesmonial.scss */
.testmonial_area .slider-nav div img {
  width: 100%;
}

/* line 18, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_tesmonial.scss */
.testmonial_area .single_slider p {
  font-size: 20px;
  line-height: 32px;
  color: #727272;
  font-weight: 400;
  text-decoration: underline;
  margin-bottom: 24px;
}

/* line 26, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_tesmonial.scss */
.testmonial_area .single_slider h4 {
  font-size: 16px;
  color: #2C2C2C;
  font-weight: 400;
  text-transform: uppercase;
}

/* line 32, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_tesmonial.scss */
.testmonial_area .single_slider span {
  color: #727272;
  font-size: 14px;
}

/* line 1, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_area {
  background: #3B2930;
  padding-bottom: 90px;
  padding-top: 120px;
}

/* line 5, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_area.colord_bg {
  background: #311E25;
}

/* line 11, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_area .single_service {
  border: 1px solid #6B4B40;
  padding: 45px 30px;
  margin-bottom: 30px;
}

/* line 15, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_area .single_service h3 {
  color: #DB9A64;
  margin-top: 22px;
  margin-bottom: 11px;
  font-weight: 400;
}

/* line 21, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_area .single_service p {
  font-size: 16px;
  color: #C9C9C9;
  line-height: 28px;
  margin-bottom: 0;
}

/* line 30, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products {
  background: #311E25;
  padding-top: 0px;
  padding-bottom: 60px;
}

/* line 34, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products .padding_left {
  padding-left: 68px;
}

@media (max-width: 767px) {
  /* line 34, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
  .service_products .padding_left {
    padding-left: 0;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  /* line 34, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
  .service_products .padding_left {
    padding-left: 0;
  }
}

/* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products .service_wrap {
  margin-bottom: 60px;
}

/* line 46, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products .service_wrap .thumb img {
  width: 100%;
}

/* line 50, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products .service_wrap .service_text {
  margin: 30px 0;
}

/* line 52, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products .service_wrap .service_text h3 {
  color: #fff;
  font-size: 36px;
  font-weight: 400;
}

/* line 57, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products .service_wrap .service_text p {
  color: #C9C9C9;
  font-size: 16px;
  line-height: 28px;
  margin: 30px 0;
}

/* line 63, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_service.scss */
.service_products .service_wrap .service_text .boxed-btn3-line {
  margin-top: 10px;
}

/*=================== contact banner start ====================*/
/* line 3, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.dropdown .dropdown-menu {
  -webkit-transition: all 0.3s;
  -moz-transition: all 0.3s;
  -ms-transition: all 0.3s;
  -o-transition: all 0.3s;
  transition: all 0.3s;
}

/* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-info {
  margin-bottom: 25px;
}

/* line 13, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-info__icon {
  margin-right: 20px;
}

/* line 16, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-info__icon i, .contact-info__icon span {
  color: #8f9195;
  font-size: 27px;
}

/* line 24, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-info .media-body h3 {
  font-size: 16px;
  margin-bottom: 0;
  font-size: 16px;
  color: #2a2a2a;
}

/* line 30, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-info .media-body h3 a:hover {
  color: #ff5e13;
}

/* line 36, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-info .media-body p {
  color: #8a8a8a;
}

/*=================== contact banner end ====================*/
/*=================== contact form start ====================*/
/* line 45, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-title {
  font-size: 27px;
  font-weight: 600;
  margin-bottom: 20px;
}

/* line 53, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.form-contact label {
  font-size: 14px;
}

/* line 57, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.form-contact .form-group {
  margin-bottom: 30px;
}

/* line 61, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.form-contact .form-control {
  border: 1px solid #e5e6e9;
  border-radius: 0px;
  height: 48px;
  padding-left: 18px;
  font-size: 13px;
  background: transparent;
}

/* line 69, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.form-contact .form-control:focus {
  outline: 0;
  box-shadow: none;
}

/* line 74, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.form-contact .form-control::placeholder {
  font-weight: 300;
  color: #999999;
}

/* line 80, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.form-contact textarea {
  border-radius: 0px;
  height: 100% !important;
}

/*=================== contact form end ====================*/
/* Contact Success and error Area css
============================================================================================ */
/* line 97, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.modal-message .modal-dialog {
  position: absolute;
  top: 36%;
  left: 50%;
  transform: translateX(-50%) translateY(-50%) !important;
  margin: 0px;
  max-width: 500px;
  width: 100%;
}

/* line 106, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.modal-message .modal-dialog .modal-content .modal-header {
  text-align: center;
  display: block;
  border-bottom: none;
  padding-top: 50px;
  padding-bottom: 50px;
}

/* line 112, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.modal-message .modal-dialog .modal-content .modal-header .close {
  position: absolute;
  right: -15px;
  top: -15px;
  padding: 0px;
  color: #fff;
  opacity: 1;
  cursor: pointer;
}

/* line 121, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.modal-message .modal-dialog .modal-content .modal-header h2 {
  display: block;
  text-align: center;
  padding-bottom: 10px;
}

/* line 126, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.modal-message .modal-dialog .modal-content .modal-header p {
  display: block;
}

/* line 133, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-section {
  padding: 130px 0 100px;
}

@media (max-width: 991px) {
  /* line 133, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
  .contact-section {
    padding: 70px 0 40px;
  }
}

@media only screen and (min-width: 992px) and (max-width: 1200px) {
  /* line 133, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
  .contact-section {
    padding: 80px 0 50px;
  }
}

/* line 141, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-section .btn_2 {
  background-color: #191d34;
  padding: 18px 60px;
  border-radius: 50px;
  margin-top: 0;
}

/* line 146, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_contact.scss */
.contact-section .btn_2:hover {
  background-color: #ff5e13;
}

/* line 75, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.sample-text-area {
  background: #fff;
  padding: 100px 0 70px 0;
}

/* line 80, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.text-heading {
  margin-bottom: 30px;
  font-size: 24px;
}

/* line 85, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
b,
sup,
sub,
u,
del {
  color: #ff5e13;
}

/* line 93, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
h1 {
  font-size: 36px;
}

/* line 97, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
h2 {
  font-size: 30px;
}

/* line 101, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
h3 {
  font-size: 24px;
}

/* line 105, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
h4 {
  font-size: 18px;
}

/* line 109, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
h5 {
  font-size: 16px;
}

/* line 113, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
h6 {
  font-size: 14px;
}

/* line 117, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
h1,
h2,
h3,
h4,
h5,
h6 {
  line-height: 1.2em;
}

/* line 127, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.typography h1,
.typography h2,
.typography h3,
.typography h4,
.typography h5,
.typography h6 {
  color: #828bb2;
}

/* line 137, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.button-area {
  background: #fff;
}

/* line 138, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.button-area .border-top-generic {
  padding: 70px 15px;
  border-top: 1px dotted #eee;
}

/* line 146, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.button-group-area .genric-btn {
  margin-right: 10px;
  margin-top: 10px;
}

/* line 149, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.button-group-area .genric-btn:last-child {
  margin-right: 0;
}

/* line 155, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn {
  display: inline-block;
  outline: none;
  line-height: 40px;
  padding: 0 30px;
  font-size: .8em;
  text-align: center;
  text-decoration: none;
  font-weight: 500;
  cursor: pointer;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
}

/* line 166, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn:focus {
  outline: none;
}

/* line 169, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.e-large {
  padding: 0 40px;
  line-height: 50px;
}

/* line 173, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.large {
  line-height: 45px;
}

/* line 176, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.medium {
  line-height: 30px;
}

/* line 179, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.small {
  line-height: 25px;
}

/* line 182, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.radius {
  border-radius: 3px;
}

/* line 185, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.circle {
  border-radius: 20px;
}

/* line 188, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.arrow {
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

/* line 195, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.arrow span {
  margin-left: 10px;
}

/* line 199, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.default {
  color: #415094;
  background: #f9f9ff;
  border: 1px solid transparent;
}

/* line 203, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.default:hover {
  border: 1px solid #f9f9ff;
  background: #fff;
}

/* line 208, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.default-border {
  border: 1px solid #f9f9ff;
  background: #fff;
}

/* line 211, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.default-border:hover {
  color: #415094;
  background: #f9f9ff;
  border: 1px solid transparent;
}

/* line 217, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.primary {
  color: #fff;
  background: #ff5e13;
  border: 1px solid transparent;
}

/* line 221, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.primary:hover {
  color: #ff5e13;
  border: 1px solid #ff5e13;
  background: #fff;
}

/* line 227, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.primary-border {
  color: #ff5e13;
  border: 1px solid #ff5e13;
  background: #fff;
}

/* line 231, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.primary-border:hover {
  color: #fff;
  background: #ff5e13;
  border: 1px solid transparent;
}

/* line 237, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.success {
  color: #fff;
  background: #4cd3e3;
  border: 1px solid transparent;
}

/* line 241, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.success:hover {
  color: #4cd3e3;
  border: 1px solid #4cd3e3;
  background: #fff;
}

/* line 247, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.success-border {
  color: #4cd3e3;
  border: 1px solid #4cd3e3;
  background: #fff;
}

/* line 251, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.success-border:hover {
  color: #fff;
  background: #4cd3e3;
  border: 1px solid transparent;
}

/* line 257, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.info {
  color: #fff;
  background: #38a4ff;
  border: 1px solid transparent;
}

/* line 261, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.info:hover {
  color: #38a4ff;
  border: 1px solid #38a4ff;
  background: #fff;
}

/* line 267, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.info-border {
  color: #38a4ff;
  border: 1px solid #38a4ff;
  background: #fff;
}

/* line 271, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.info-border:hover {
  color: #fff;
  background: #38a4ff;
  border: 1px solid transparent;
}

/* line 277, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.warning {
  color: #fff;
  background: #f4e700;
  border: 1px solid transparent;
}

/* line 281, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.warning:hover {
  color: #f4e700;
  border: 1px solid #f4e700;
  background: #fff;
}

/* line 287, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.warning-border {
  color: #f4e700;
  border: 1px solid #f4e700;
  background: #fff;
}

/* line 291, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.warning-border:hover {
  color: #fff;
  background: #f4e700;
  border: 1px solid transparent;
}

/* line 297, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.danger {
  color: #fff;
  background: #f44a40;
  border: 1px solid transparent;
}

/* line 301, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.danger:hover {
  color: #f44a40;
  border: 1px solid #f44a40;
  background: #fff;
}

/* line 307, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.danger-border {
  color: #f44a40;
  border: 1px solid #f44a40;
  background: #fff;
}

/* line 311, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.danger-border:hover {
  color: #fff;
  background: #f44a40;
  border: 1px solid transparent;
}

/* line 317, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.link {
  color: #415094;
  background: #f9f9ff;
  text-decoration: underline;
  border: 1px solid transparent;
}

/* line 322, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.link:hover {
  color: #415094;
  border: 1px solid #f9f9ff;
  background: #fff;
}

/* line 328, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.link-border {
  color: #415094;
  border: 1px solid #f9f9ff;
  background: #fff;
  text-decoration: underline;
}

/* line 333, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.link-border:hover {
  color: #415094;
  background: #f9f9ff;
  border: 1px solid transparent;
}

/* line 339, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.genric-btn.disable {
  color: #222222, 0.3;
  background: #f9f9ff;
  border: 1px solid transparent;
  cursor: not-allowed;
}

/* line 347, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.generic-blockquote {
  padding: 30px 50px 30px 30px;
  background: #f9f9ff;
  border-left: 2px solid #ff5e13;
}

/* line 353, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table-wrap {
  overflow-x: scroll;
}

/* line 357, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table {
  background: #f9f9ff;
  padding: 15px 0px 30px 0px;
  min-width: 800px;
}

/* line 361, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .serial {
  width: 11.83%;
  padding-left: 30px;
}

/* line 365, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .country {
  width: 28.07%;
}

/* line 368, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .visit {
  width: 19.74%;
}

/* line 371, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .percentage {
  width: 40.36%;
  padding-right: 50px;
}

/* line 375, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-head {
  display: flex;
}

/* line 377, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-head .serial,
.progress-table .table-head .country,
.progress-table .table-head .visit,
.progress-table .table-head .percentage {
  color: #415094;
  line-height: 40px;
  text-transform: uppercase;
  font-weight: 500;
}

/* line 387, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row {
  padding: 15px 0;
  border-top: 1px solid #edf3fd;
  display: flex;
}

/* line 391, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .serial,
.progress-table .table-row .country,
.progress-table .table-row .visit,
.progress-table .table-row .percentage {
  display: flex;
  align-items: center;
}

/* line 399, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .country img {
  margin-right: 15px;
}

/* line 404, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress {
  width: 80%;
  border-radius: 0px;
  background: transparent;
}

/* line 408, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar {
  height: 5px;
  line-height: 5px;
}

/* line 411, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-1 {
  background-color: #6382e6;
}

/* line 414, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-2 {
  background-color: #e66686;
}

/* line 417, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-3 {
  background-color: #f09359;
}

/* line 420, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-4 {
  background-color: #73fbaf;
}

/* line 423, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-5 {
  background-color: #73fbaf;
}

/* line 426, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-6 {
  background-color: #6382e6;
}

/* line 429, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-7 {
  background-color: #a367e7;
}

/* line 432, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.progress-table .table-row .percentage .progress .progress-bar.color-8 {
  background-color: #e66686;
}

/* line 441, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-gallery-image {
  margin-top: 30px;
  background-repeat: no-repeat !important;
  background-position: center center !important;
  background-size: cover !important;
  height: 200px;
}

/* line 449, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.list-style {
  width: 14px;
  height: 14px;
}

/* line 455, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.unordered-list li {
  position: relative;
  padding-left: 30px;
  line-height: 1.82em !important;
}

/* line 459, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.unordered-list li:before {
  content: "";
  position: absolute;
  width: 14px;
  height: 14px;
  border: 3px solid #ff5e13;
  background: #fff;
  top: 4px;
  left: 0;
  border-radius: 50%;
}

/* line 473, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.ordered-list {
  margin-left: 30px;
}

/* line 475, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.ordered-list li {
  list-style-type: decimal-leading-zero;
  color: #ff5e13;
  font-weight: 500;
  line-height: 1.82em !important;
}

/* line 480, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.ordered-list li span {
  font-weight: 300;
  color: #828bb2;
}

/* line 488, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.ordered-list-alpha li {
  margin-left: 30px;
  list-style-type: lower-alpha;
  color: #ff5e13;
  font-weight: 500;
  line-height: 1.82em !important;
}

/* line 494, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.ordered-list-alpha li span {
  font-weight: 300;
  color: #828bb2;
}

/* line 502, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.ordered-list-roman li {
  margin-left: 30px;
  list-style-type: lower-roman;
  color: #ff5e13;
  font-weight: 500;
  line-height: 1.82em !important;
}

/* line 508, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.ordered-list-roman li span {
  font-weight: 300;
  color: #828bb2;
}

/* line 515, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input {
  display: block;
  width: 100%;
  line-height: 40px;
  border: none;
  outline: none;
  background: #f9f9ff;
  padding: 0 20px;
}

/* line 523, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input:focus {
  outline: none;
}

/* line 528, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.input-group-icon {
  position: relative;
}

/* line 530, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.input-group-icon .icon {
  position: absolute;
  left: 20px;
  top: 0;
  line-height: 40px;
  z-index: 3;
}

/* line 535, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.input-group-icon .icon i {
  color: #797979;
}

/* line 540, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.input-group-icon .single-input {
  padding-left: 45px;
}

/* line 545, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-textarea {
  display: block;
  width: 100%;
  line-height: 40px;
  border: none;
  outline: none;
  background: #f9f9ff;
  padding: 0 20px;
  height: 100px;
  resize: none;
}

/* line 555, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-textarea:focus {
  outline: none;
}

/* line 560, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input-primary {
  display: block;
  width: 100%;
  line-height: 40px;
  border: 1px solid transparent;
  outline: none;
  background: #f9f9ff;
  padding: 0 20px;
}

/* line 568, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input-primary:focus {
  outline: none;
  border: 1px solid #ff5e13;
}

/* line 574, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input-accent {
  display: block;
  width: 100%;
  line-height: 40px;
  border: 1px solid transparent;
  outline: none;
  background: #f9f9ff;
  padding: 0 20px;
}

/* line 582, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input-accent:focus {
  outline: none;
  border: 1px solid #eb6b55;
}

/* line 588, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input-secondary {
  display: block;
  width: 100%;
  line-height: 40px;
  border: 1px solid transparent;
  outline: none;
  background: #f9f9ff;
  padding: 0 20px;
}

/* line 596, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.single-input-secondary:focus {
  outline: none;
  border: 1px solid #f09359;
}

/* line 602, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-switch {
  width: 35px;
  height: 17px;
  border-radius: 8.5px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 609, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-switch input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  cursor: pointer;
}

/* line 619, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-switch input + label {
  position: absolute;
  top: 1px;
  left: 1px;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background: #ff5e13;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  -o-transition: all 0.2s;
  transition: all 0.2s;
  box-shadow: 0px 4px 5px 0px rgba(0, 0, 0, 0.2);
  cursor: pointer;
}

/* line 632, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-switch input:checked + label {
  left: 19px;
}

/* line 639, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-switch {
  width: 35px;
  height: 17px;
  border-radius: 8.5px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 646, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-switch input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 655, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-switch input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
}

/* line 663, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-switch input + label:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  background: transparent;
  border-radius: 8.5px;
  cursor: pointer;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  -o-transition: all 0.2s;
  transition: all 0.2s;
}

/* line 677, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-switch input + label:after {
  content: "";
  position: absolute;
  top: 1px;
  left: 1px;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background: #fff;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  -o-transition: all 0.2s;
  transition: all 0.2s;
  box-shadow: 0px 4px 5px 0px rgba(0, 0, 0, 0.2);
  cursor: pointer;
}

/* line 693, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-switch input:checked + label:after {
  left: 19px;
}

/* line 696, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-switch input:checked + label:before {
  background: #ff5e13;
}

/* line 704, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-switch {
  width: 35px;
  height: 17px;
  border-radius: 8.5px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 711, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-switch input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 720, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-switch input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
}

/* line 728, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-switch input + label:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  background: transparent;
  border-radius: 8.5px;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  -o-transition: all 0.2s;
  transition: all 0.2s;
  cursor: pointer;
}

/* line 742, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-switch input + label:after {
  content: "";
  position: absolute;
  top: 1px;
  left: 1px;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background: #fff;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  -o-transition: all 0.2s;
  transition: all 0.2s;
  box-shadow: 0px 4px 5px 0px rgba(0, 0, 0, 0.2);
  cursor: pointer;
}

/* line 758, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-switch input:checked + label:after {
  left: 19px;
}

/* line 761, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-switch input:checked + label:before {
  background: #4cd3e3;
}

/* line 769, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-checkbox {
  width: 16px;
  height: 16px;
  border-radius: 3px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 776, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-checkbox input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 785, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-checkbox input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  border-radius: 3px;
  cursor: pointer;
  border: 1px solid #f1f1f1;
}

/* line 798, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-checkbox input:checked + label {
  background: url(../img/elements/primary-check.png) no-repeat center center/cover;
  border: none;
}

/* line 806, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-checkbox {
  width: 16px;
  height: 16px;
  border-radius: 3px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 813, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-checkbox input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 822, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-checkbox input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  border-radius: 3px;
  cursor: pointer;
  border: 1px solid #f1f1f1;
}

/* line 835, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-checkbox input:checked + label {
  background: url(../img/elements/success-check.png) no-repeat center center/cover;
  border: none;
}

/* line 843, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-checkbox {
  width: 16px;
  height: 16px;
  border-radius: 3px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 850, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-checkbox input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 859, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-checkbox input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  border-radius: 3px;
  cursor: pointer;
  border: 1px solid #f1f1f1;
}

/* line 871, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-checkbox input:disabled {
  cursor: not-allowed;
  z-index: 3;
}

/* line 876, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-checkbox input:checked + label {
  background: url(../img/elements/disabled-check.png) no-repeat center center/cover;
  border: none;
}

/* line 884, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-radio {
  width: 16px;
  height: 16px;
  border-radius: 8px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 891, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-radio input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 900, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-radio input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  border-radius: 8px;
  cursor: pointer;
  border: 1px solid #f1f1f1;
}

/* line 913, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.primary-radio input:checked + label {
  background: url(../img/elements/primary-radio.png) no-repeat center center/cover;
  border: none;
}

/* line 921, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-radio {
  width: 16px;
  height: 16px;
  border-radius: 8px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 928, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-radio input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 937, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-radio input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  border-radius: 8px;
  cursor: pointer;
  border: 1px solid #f1f1f1;
}

/* line 950, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.confirm-radio input:checked + label {
  background: url(../img/elements/success-radio.png) no-repeat center center/cover;
  border: none;
}

/* line 958, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-radio {
  width: 16px;
  height: 16px;
  border-radius: 8px;
  background: #f9f9ff;
  position: relative;
  cursor: pointer;
}

/* line 965, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-radio input {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
}

/* line 974, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-radio input + label {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  border-radius: 8px;
  cursor: pointer;
  border: 1px solid #f1f1f1;
}

/* line 986, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-radio input:disabled {
  cursor: not-allowed;
  z-index: 3;
}

/* line 991, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.disabled-radio input:checked + label {
  background: url(../img/elements/disabled-radio.png) no-repeat center center/cover;
  border: none;
}

/* line 999, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select {
  height: 40px;
}

/* line 1001, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select .nice-select {
  border: none;
  border-radius: 0px;
  height: 40px;
  background: #f9f9ff;
  padding-left: 20px;
  padding-right: 40px;
}

/* line 1008, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select .nice-select .list {
  margin-top: 0;
  border: none;
  border-radius: 0px;
  box-shadow: none;
  width: 100%;
  padding: 10px 0 10px 0px;
}

/* line 1015, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select .nice-select .list .option {
  font-weight: 300;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  line-height: 28px;
  min-height: 28px;
  font-size: 12px;
  padding-left: 20px;
}

/* line 1022, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select .nice-select .list .option.selected {
  color: #ff5e13;
  background: transparent;
}

/* line 1026, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select .nice-select .list .option:hover {
  color: #ff5e13;
  background: transparent;
}

/* line 1033, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select .current {
  margin-right: 50px;
  font-weight: 300;
}

/* line 1037, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.default-select .nice-select::after {
  right: 20px;
}

/* line 1042, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select {
  height: 40px;
  width: 100%;
}

/* line 1045, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select .nice-select {
  border: none;
  border-radius: 0px;
  height: 40px;
  background: #f9f9ff;
  padding-left: 45px;
  padding-right: 40px;
  width: 100%;
}

/* line 1053, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select .nice-select .list {
  margin-top: 0;
  border: none;
  border-radius: 0px;
  box-shadow: none;
  width: 100%;
  padding: 10px 0 10px 0px;
}

/* line 1060, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select .nice-select .list .option {
  font-weight: 300;
  -webkit-transition: all 0.3s ease 0s;
  -moz-transition: all 0.3s ease 0s;
  -o-transition: all 0.3s ease 0s;
  transition: all 0.3s ease 0s;
  line-height: 28px;
  min-height: 28px;
  font-size: 12px;
  padding-left: 45px;
}

/* line 1067, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select .nice-select .list .option.selected {
  color: #ff5e13;
  background: transparent;
}

/* line 1071, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select .nice-select .list .option:hover {
  color: #ff5e13;
  background: transparent;
}

/* line 1078, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select .current {
  margin-right: 50px;
  font-weight: 300;
}

/* line 1082, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.form-select .nice-select::after {
  right: 20px;
}

/* line 1086, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.mt-10 {
  margin-top: 10px;
}

/* line 1089, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.section-top-border {
  padding: 50px 0;
  border-top: 1px dotted #eee;
}

/* line 1093, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.mb-30 {
  margin-bottom: 30px;
}

/* line 1096, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.mt-30 {
  margin-top: 30px;
}

/* line 1099, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_elements.scss */
.switch-wrap {
  margin-bottom: 10px;
}

/* Start Blog Area css
============================================================================================ */
/* line 5, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.latest-blog-area .area-heading {
  margin-bottom: 70px;
}

/* line 10, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_area a {
  color: #666666 !important;
  text-decoration: none;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 14, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_area a:hover, .blog_area a :hover {
  background: -webkit-linear-gradient(131deg, #DB9A64 0%, #DB9A64 99%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-decoration: none;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 24, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog {
  overflow: hidden;
  margin-bottom: 30px;
}

/* line 28, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog:hover {
  box-shadow: 0px 10px 20px 0px rgba(42, 34, 123, 0.1);
}

/* line 32, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .thumb {
  overflow: hidden;
  position: relative;
}

/* line 36, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .thumb:after {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: #000;
  opacity: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 49, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog h4 {
  border-bottom: 1px solid #dfdfdf;
  padding-bottom: 34px;
  margin-bottom: 25px;
}

/* line 56, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog a {
  font-size: 20px;
  font-weight: 600;
}

/* line 66, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .date {
  color: #666666;
  text-align: left;
  display: inline-block;
  font-size: 13px;
  font-weight: 300;
}

/* line 74, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .tag {
  text-align: left;
  display: inline-block;
  float: left;
  font-size: 13px;
  font-weight: 300;
  margin-right: 22px;
  position: relative;
}

/* line 84, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .tag:after {
  content: '';
  position: absolute;
  width: 1px;
  height: 10px;
  background: #acacac;
  right: -12px;
  top: 7px;
}

@media (max-width: 1199px) {
  /* line 74, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-blog .tag {
    margin-right: 8px;
  }
  /* line 98, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-blog .tag:after {
    display: none;
  }
}

/* line 104, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .likes {
  margin-right: 16px;
}

@media (max-width: 800px) {
  /* line 24, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-blog {
    margin-bottom: 30px;
  }
}

/* line 112, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .single-blog-content {
  padding: 30px;
}

/* line 116, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .single-blog-content .meta-bottom p {
  font-size: 13px;
  font-weight: 300;
}

/* line 121, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog .single-blog-content .meta-bottom i {
  color: #fdcb9e;
  font-size: 13px;
  margin-right: 7px;
}

@media (max-width: 1199px) {
  /* line 112, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-blog .single-blog-content {
    padding: 15px;
  }
}

/* line 135, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-blog:hover .thumb:after {
  opacity: .7;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

@media (max-width: 1199px) {
  /* line 143, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-blog h4 {
    transition: all 300ms linear 0s;
    border-bottom: 1px solid #dfdfdf;
    padding-bottom: 14px;
    margin-bottom: 12px;
  }
  /* line 149, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-blog h4 a {
    font-size: 18px;
  }
}

/* line 157, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.full_image.single-blog {
  position: relative;
}

/* line 160, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.full_image.single-blog .single-blog-content {
  position: absolute;
  left: 35px;
  bottom: 0;
  opacity: 0;
  visibility: hidden;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

@media (min-width: 992px) {
  /* line 160, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .full_image.single-blog .single-blog-content {
    bottom: 100px;
  }
}

/* line 179, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.full_image.single-blog h4 {
  -webkit-transition: 0.5s;
  transition: 0.5s;
  border-bottom: none;
  padding-bottom: 5px;
}

/* line 185, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.full_image.single-blog a {
  font-size: 20px;
  font-weight: 600;
}

/* line 195, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.full_image.single-blog .date {
  color: #fff;
}

/* line 200, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.full_image.single-blog:hover .single-blog-content {
  opacity: 1;
  visibility: visible;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* End Blog Area css
============================================================================================ */
/* Latest Blog Area css
============================================================================================ */
/* line 224, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.l_blog_item .l_blog_text .date {
  margin-top: 24px;
  margin-bottom: 15px;
}

/* line 228, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.l_blog_item .l_blog_text .date a {
  font-size: 12px;
}

/* line 234, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.l_blog_item .l_blog_text h4 {
  font-size: 18px;
  border-bottom: 1px solid #eeeeee;
  margin-bottom: 0px;
  padding-bottom: 20px;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 247, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.l_blog_item .l_blog_text p {
  margin-bottom: 0px;
  padding-top: 20px;
}

/* End Latest Blog Area css
============================================================================================ */
/* Causes Area css
============================================================================================ */
/* line 263, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_slider .owl-dots {
  text-align: center;
  margin-top: 80px;
}

/* line 267, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_slider .owl-dots .owl-dot {
  height: 14px;
  width: 14px;
  background: #eeeeee;
  display: inline-block;
  margin-right: 7px;
}

/* line 274, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_slider .owl-dots .owl-dot:last-child {
  margin-right: 0px;
}

/* line 285, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item {
  background: #fff;
}

/* line 288, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_img {
  position: relative;
}

/* line 291, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_img .c_parcent {
  position: absolute;
  bottom: 0px;
  width: 100%;
  left: 0px;
  height: 3px;
  background: rgba(255, 255, 255, 0.5);
}

/* line 299, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_img .c_parcent span {
  width: 70%;
  height: 3px;
  position: absolute;
  left: 0px;
  bottom: 0px;
}

/* line 307, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_img .c_parcent span:before {
  content: "75%";
  position: absolute;
  right: -10px;
  bottom: 0px;
  color: #fff;
  padding: 0px 5px;
}

/* line 320, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_text {
  padding: 30px 35px 40px 30px;
}

/* line 323, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_text h4 {
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 15px;
  cursor: pointer;
}

/* line 336, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_text p {
  font-size: 14px;
  line-height: 24px;
  font-weight: 300;
  margin-bottom: 0px;
}

/* line 346, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_bottom a {
  width: 50%;
  border: 1px solid;
  text-align: center;
  float: left;
  line-height: 50px;
  color: #fff;
  font-size: 14px;
  font-weight: 500;
}

/* line 358, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.causes_item .causes_bottom a + a {
  border-color: #eeeeee;
  background: #fff;
  font-size: 14px;
}

/* End Causes Area css
============================================================================================ */
/*================= latest_blog_area css =============*/
/* line 374, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.latest_blog_area {
  background: #f9f9ff;
}

/* line 378, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-recent-blog-post {
  margin-bottom: 30px;
}

/* line 381, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-recent-blog-post .thumb {
  overflow: hidden;
}

/* line 384, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-recent-blog-post .thumb img {
  transition: all 0.7s linear;
}

/* line 389, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-recent-blog-post .details {
  padding-top: 30px;
}

/* line 392, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-recent-blog-post .details .sec_h4 {
  line-height: 24px;
  padding: 10px 0px 13px;
  transition: all 0.3s linear;
}

/* line 403, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-recent-blog-post .date {
  font-size: 14px;
  line-height: 24px;
  font-weight: 400;
}

/* line 410, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-recent-blog-post:hover img {
  transform: scale(1.23) rotate(10deg);
}

/* line 417, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.tags .tag_btn {
  font-size: 12px;
  font-weight: 500;
  line-height: 20px;
  border: 1px solid #eeeeee;
  display: inline-block;
  padding: 1px 18px;
  text-align: center;
}

/* line 431, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.tags .tag_btn + .tag_btn {
  margin-left: 2px;
}

/*========= blog_categorie_area css ===========*/
/* line 438, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_categorie_area {
  padding-top: 30px;
  padding-bottom: 30px;
}

@media (min-width: 900px) {
  /* line 438, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .blog_categorie_area {
    padding-top: 80px;
    padding-bottom: 80px;
  }
}

@media (min-width: 1100px) {
  /* line 438, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .blog_categorie_area {
    padding-top: 120px;
    padding-bottom: 120px;
  }
}

/* line 454, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.categories_post {
  position: relative;
  text-align: center;
  cursor: pointer;
}

/* line 459, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.categories_post img {
  max-width: 100%;
}

/* line 463, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.categories_post .categories_details {
  position: absolute;
  top: 20px;
  left: 20px;
  right: 20px;
  bottom: 20px;
  background: rgba(34, 34, 34, 0.75);
  color: #fff;
  transition: all 0.3s linear;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* line 476, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.categories_post .categories_details h5 {
  margin-bottom: 0px;
  font-size: 18px;
  line-height: 26px;
  text-transform: uppercase;
  color: #fff;
  position: relative;
}

/* line 494, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.categories_post .categories_details p {
  font-weight: 300;
  font-size: 14px;
  line-height: 26px;
  margin-bottom: 0px;
}

/* line 501, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.categories_post .categories_details .border_line {
  margin: 10px 0px;
  background: #fff;
  width: 100%;
  height: 1px;
}

/* line 510, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.categories_post:hover .categories_details {
  background: rgba(222, 99, 32, 0.85);
}

/*============ blog_left_sidebar css ==============*/
/* line 525, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_item {
  margin-bottom: 50px;
}

/* line 529, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_details {
  padding: 30px 0 20px 10px;
  box-shadow: 0px 10px 20px 0px rgba(221, 221, 221, 0.3);
}

@media (min-width: 768px) {
  /* line 529, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .blog_details {
    padding: 60px 30px 35px 35px;
  }
}

/* line 537, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_details p {
  margin-bottom: 30px;
  font-family: "Roboto", sans-serif;
}

/* line 542, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_details a {
  color: #ff8b23;
}

/* line 545, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_details a:hover {
  color: #DB9A64;
}

/* line 550, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_details h2 {
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 8px;
}

@media (min-width: 768px) {
  /* line 550, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .blog_details h2 {
    font-size: 24px;
    margin-bottom: 15px;
  }
}

/* line 564, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-info-link li {
  float: left;
  font-size: 14px;
}

/* line 568, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-info-link li a {
  color: #999999;
}

/* line 572, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-info-link li i,
.blog-info-link li span {
  font-size: 13px;
  margin-right: 5px;
}

/* line 578, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-info-link li::after {
  content: "|";
  padding-left: 10px;
  padding-right: 10px;
}

/* line 584, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-info-link li:last-child::after {
  display: none;
}

/* line 589, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-info-link::after {
  content: "";
  display: block;
  clear: both;
  display: table;
}

/* line 597, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_item_img {
  position: relative;
}

/* line 600, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_item_img .blog_item_date {
  position: absolute;
  bottom: -10px;
  left: 10px;
  display: block;
  color: #fff;
  background-color: #F91842;
  padding: 8px 15px;
  border-radius: 5px;
}

@media (min-width: 768px) {
  /* line 600, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .blog_item_img .blog_item_date {
    bottom: -20px;
    left: 40px;
    padding: 13px 30px;
  }
}

/* line 616, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_item_img .blog_item_date h3 {
  font-size: 22px;
  font-weight: 600;
  color: #fff;
  margin-bottom: 0;
  line-height: 1.2;
}

@media (min-width: 768px) {
  /* line 616, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .blog_item_img .blog_item_date h3 {
    font-size: 30px;
  }
}

/* line 628, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_item_img .blog_item_date p {
  font-size: 18px;
  margin-bottom: 0;
  color: #fff;
}

@media (min-width: 768px) {
  /* line 628, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .blog_item_img .blog_item_date p {
    font-size: 18px;
  }
}

/* line 648, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .widget_title {
  font-size: 20px;
  margin-bottom: 40px;
}

/* line 653, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .widget_title::after {
  content: "";
  display: block;
  padding-top: 15px;
  border-bottom: 1px solid #f0e9ff;
}

/* line 661, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .single_sidebar_widget {
  background: #fbf9ff;
  padding: 30px;
  margin-bottom: 30px;
}

/* line 665, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .single_sidebar_widget .btn_1 {
  margin-top: 0px;
}

/* line 673, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .search_widget .form-control {
  height: 50px;
  border-color: #f0e9ff;
  font-size: 13px;
  color: #999999;
  padding-left: 20px;
  border-radius: 0;
  border-right: 0;
}

/* line 682, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .search_widget .form-control::placeholder {
  color: #999999;
}

/* line 686, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .search_widget .form-control:focus {
  border-color: #f0e9ff;
  outline: 0;
  box-shadow: none;
}

/* line 695, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .search_widget .input-group button {
  background: #fff;
  border-left: 0;
  border: 1px solid #f0e9ff;
  padding: 4px 15px;
  border-left: 0;
}

/* line 702, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .search_widget .input-group button i,
.blog_right_sidebar .search_widget .input-group button span {
  font-size: 14px;
  color: #999999;
}

/* line 714, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .newsletter_widget .form-control {
  height: 50px;
  border-color: #f0e9ff;
  font-size: 13px;
  color: #999999;
  padding-left: 20px;
  border-radius: 0;
}

/* line 723, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .newsletter_widget .form-control::placeholder {
  color: #999999;
}

/* line 727, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .newsletter_widget .form-control:focus {
  border-color: #f0e9ff;
  outline: 0;
  box-shadow: none;
}

/* line 736, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .newsletter_widget .input-group button {
  background: #fff;
  border-left: 0;
  border: 1px solid #f0e9ff;
  padding: 4px 15px;
  border-left: 0;
}

/* line 743, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .newsletter_widget .input-group button i,
.blog_right_sidebar .newsletter_widget .input-group button span {
  font-size: 14px;
  color: #999999;
}

/* line 756, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .post_category_widget .cat-list li {
  border-bottom: 1px solid #f0e9ff;
  transition: all 0.3s ease 0s;
  padding-bottom: 12px;
}

/* line 761, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .post_category_widget .cat-list li:last-child {
  border-bottom: 0;
}

/* line 765, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .post_category_widget .cat-list li a {
  font-size: 14px;
  line-height: 20px;
  color: #888888;
}

/* line 770, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .post_category_widget .cat-list li a p {
  margin-bottom: 0px;
}

/* line 775, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .post_category_widget .cat-list li + li {
  padding-top: 15px;
}

/* line 792, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .popular_post_widget .post_item .media-body {
  justify-content: center;
  align-self: center;
  padding-left: 20px;
}

/* line 797, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .popular_post_widget .post_item .media-body h3 {
  font-size: 16px;
  line-height: 20px;
  margin-bottom: 6px;
  transition: all 0.3s linear;
}

/* line 808, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .popular_post_widget .post_item .media-body a:hover {
  color: #fff;
}

/* line 814, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .popular_post_widget .post_item .media-body p {
  font-size: 14px;
  line-height: 21px;
  margin-bottom: 0px;
}

/* line 821, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .popular_post_widget .post_item + .post_item {
  margin-top: 20px;
}

/* line 829, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .tag_cloud_widget ul li {
  display: inline-block;
}

/* line 832, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .tag_cloud_widget ul li a {
  display: inline-block;
  border: 1px solid #eeeeee;
  background: #fff;
  padding: 4px 20px;
  margin-bottom: 8px;
  margin-right: 3px;
  transition: all 0.3s ease 0s;
  color: #888888;
  font-size: 13px;
}

/* line 843, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .tag_cloud_widget ul li a:hover {
  background: #DB9A64;
  color: #fff !important;
  -webkit-text-fill-color: #fff;
  text-decoration: none;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 858, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .instagram_feeds .instagram_row {
  display: flex;
  margin-right: -6px;
  margin-left: -6px;
}

/* line 864, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .instagram_feeds .instagram_row li {
  width: 33.33%;
  float: left;
  padding-right: 6px;
  padding-left: 6px;
  margin-bottom: 15px;
}

/* line 964, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog_right_sidebar .br {
  width: 100%;
  height: 1px;
  background: #eeeeee;
  margin: 30px 0px;
}

/* line 985, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-pagination {
  margin-top: 80px;
}

/* line 989, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-pagination .page-link {
  font-size: 14px;
  position: relative;
  display: block;
  padding: 0;
  text-align: center;
  margin-left: -1px;
  line-height: 45px;
  width: 45px;
  height: 45px;
  border-radius: 0 !important;
  color: #8a8a8a;
  border: 1px solid #f0e9ff;
  margin-right: 10px;
}

/* line 1006, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-pagination .page-link i,
.blog-pagination .page-link span {
  font-size: 13px;
}

/* line 1018, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-pagination .page-item.active .page-link {
  background-color: #fbf9ff;
  border-color: #f0e9ff;
  color: #888888;
}

/* line 1025, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.blog-pagination .page-item:last-child .page-link {
  margin-right: 0;
}

/*============ Start Blog Single Styles  =============*/
/* line 1050, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog_details {
  box-shadow: none;
  padding: 0;
}

/* line 1055, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .social-links {
  padding-top: 10px;
}

/* line 1058, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .social-links li {
  display: inline-block;
  margin-bottom: 10px;
}

/* line 1062, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .social-links li a {
  color: #cccccc;
  padding: 7px;
  font-size: 14px;
  transition: all 0.2s linear;
}

/* line 1075, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog_details {
  padding-top: 26px;
}

/* line 1078, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog_details p {
  margin-bottom: 20px;
  font-size: 15px;
}

/* line 1088, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .quote-wrapper {
  background: rgba(130, 139, 178, 0.1);
  padding: 15px;
  line-height: 1.733;
  color: #888888;
  font-style: italic;
  margin-top: 25px;
  margin-bottom: 25px;
}

@media (min-width: 768px) {
  /* line 1088, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-post-area .quote-wrapper {
    padding: 30px;
  }
}

/* line 1102, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .quotes {
  background: #fff;
  padding: 15px 15px 15px 20px;
  border-left: 2px solid;
  font-family: "Roboto", sans-serif;
}

@media (min-width: 768px) {
  /* line 1102, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-post-area .quotes {
    padding: 25px 25px 25px 30px;
  }
}

/* line 1112, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .arrow {
  position: absolute;
}

/* line 1115, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .arrow .lnr {
  font-size: 20px;
  font-weight: 600;
}

/* line 1122, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .thumb .overlay-bg {
  background: rgba(0, 0, 0, 0.8);
}

/* line 1127, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top {
  padding-top: 15px;
  border-top: 1px solid #f0e9ff;
}

/* line 1131, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top p {
  margin-bottom: 0;
}

/* line 1135, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top .like-info {
  font-size: 14px;
}

/* line 1138, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top .like-info i,
.single-post-area .navigation-top .like-info span {
  font-size: 16px;
  margin-right: 5px;
}

/* line 1145, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top .comment-count {
  font-size: 14px;
}

/* line 1148, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top .comment-count i,
.single-post-area .navigation-top .comment-count span {
  font-size: 16px;
  margin-right: 5px;
}

/* line 1157, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top .social-icons li {
  display: inline-block;
  margin-right: 15px;
}

/* line 1161, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top .social-icons li:last-child {
  margin: 0;
}

/* line 1165, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-top .social-icons li i,
.single-post-area .navigation-top .social-icons li span {
  font-size: 14px;
  color: #999999;
}

/* line 1183, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog-author {
  padding: 40px 30px;
  background: #fbf9ff;
  margin-top: 50px;
}

@media (max-width: 600px) {
  /* line 1183, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-post-area .blog-author {
    padding: 20px 8px;
  }
}

/* line 1192, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog-author img {
  width: 90px;
  height: 90px;
  border-radius: 50%;
  margin-right: 30px;
}

@media (max-width: 600px) {
  /* line 1192, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-post-area .blog-author img {
    margin-right: 15px;
    width: 45px;
    height: 45px;
  }
}

/* line 1205, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog-author a {
  display: inline-block;
}

/* line 1209, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog-author a:hover {
  color: #DB9A64;
}

/* line 1214, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog-author p {
  margin-bottom: 0;
  font-size: 15px;
}

/* line 1219, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .blog-author h4 {
  font-size: 16px;
}

/* line 1226, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area {
  border-bottom: 1px solid #eee;
  padding-bottom: 30px;
  margin-top: 55px;
}

/* line 1231, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area p {
  margin-bottom: 0px;
}

/* line 1235, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area h4 {
  font-size: 18px;
  line-height: 25px;
}

/* line 1241, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-left {
  text-align: left;
}

/* line 1244, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-left .thumb {
  margin-right: 20px;
  background: #000;
}

/* line 1248, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-left .thumb img {
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 1253, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-left .lnr {
  margin-left: 20px;
  opacity: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 1260, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-left:hover .lnr {
  opacity: 1;
}

/* line 1265, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-left:hover .thumb img {
  opacity: .5;
}

@media (max-width: 767px) {
  /* line 1241, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-post-area .navigation-area .nav-left {
    margin-bottom: 30px;
  }
}

/* line 1276, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-right {
  text-align: right;
}

/* line 1279, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-right .thumb {
  margin-left: 20px;
  background: #000;
}

/* line 1283, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-right .thumb img {
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 1288, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-right .lnr {
  margin-right: 20px;
  opacity: 0;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

/* line 1295, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-right:hover .lnr {
  opacity: 1;
}

/* line 1300, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.single-post-area .navigation-area .nav-right:hover .thumb img {
  opacity: .5;
}

@media (max-width: 991px) {
  /* line 1308, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .single-post-area .sidebar-widgets {
    padding-bottom: 0px;
  }
}

/* line 1315, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area {
  background: transparent;
  border-top: 1px solid #eee;
  padding: 45px 0;
  margin-top: 50px;
}

@media (max-width: 414px) {
  /* line 1315, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .comments-area {
    padding: 50px 8px;
  }
}

/* line 1326, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area h4 {
  margin-bottom: 35px;
  font-size: 18px;
}

/* line 1333, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area h5 {
  font-size: 16px;
  margin-bottom: 0px;
}

/* line 1342, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .comment-list {
  padding-bottom: 48px;
}

/* line 1345, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .comment-list:last-child {
  padding-bottom: 0px;
}

/* line 1349, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .comment-list.left-padding {
  padding-left: 25px;
}

@media (max-width: 413px) {
  /* line 1355, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .comments-area .comment-list .single-comment h5 {
    font-size: 12px;
  }
  /* line 1359, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .comments-area .comment-list .single-comment .date {
    font-size: 11px;
  }
  /* line 1363, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .comments-area .comment-list .single-comment .comment {
    font-size: 10px;
  }
}

/* line 1370, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .thumb {
  margin-right: 20px;
}

/* line 1373, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .thumb img {
  width: 70px;
  border-radius: 50%;
}

/* line 1379, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .date {
  font-size: 14px;
  color: #999999;
  margin-bottom: 0;
  margin-left: 20px;
}

/* line 1386, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .comment {
  margin-bottom: 10px;
  color: #777777;
  font-size: 15px;
  font-family: "Roboto", sans-serif;
}

/* line 1393, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comments-area .btn-reply {
  background-color: transparent;
  color: #888888;
  padding: 5px 18px;
  font-size: 14px;
  display: block;
  font-weight: 400;
}

/* line 1410, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form {
  border-top: 1px solid #eee;
  padding-top: 45px;
  margin-top: 50px;
  margin-bottom: 20px;
}

/* line 1418, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form .form-group {
  margin-bottom: 30px;
}

/* line 1422, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form h4 {
  margin-bottom: 40px;
  font-size: 18px;
  line-height: 22px;
}

/* line 1430, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form .name {
  padding-left: 0px;
}

@media (max-width: 767px) {
  /* line 1430, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .comment-form .name {
    padding-right: 0px;
    margin-bottom: 1rem;
  }
}

/* line 1439, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form .email {
  padding-right: 0px;
}

@media (max-width: 991px) {
  /* line 1439, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
  .comment-form .email {
    padding-left: 0px;
  }
}

/* line 1447, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form .form-control {
  border: 1px solid #f0e9ff;
  border-radius: 5px;
  height: 48px;
  padding-left: 18px;
  font-size: 13px;
  background: transparent;
}

/* line 1455, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form .form-control:focus {
  outline: 0;
  box-shadow: none;
}

/* line 1460, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form .form-control::placeholder {
  font-weight: 300;
  color: #999999;
}

/* line 1465, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form .form-control::placeholder {
  color: #777777;
}

/* line 1470, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form textarea {
  padding-top: 18px;
  border-radius: 12px;
  height: 100% !important;
}

/* line 1476, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form ::-webkit-input-placeholder {
  /* Chrome/Opera/Safari */
  font-size: 13px;
  color: #777;
}

/* line 1482, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form ::-moz-placeholder {
  /* Firefox 19+ */
  font-size: 13px;
  color: #777;
}

/* line 1488, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form :-ms-input-placeholder {
  /* IE 10+ */
  font-size: 13px;
  color: #777;
}

/* line 1494, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog.scss */
.comment-form :-moz-placeholder {
  /* Firefox 18- */
  font-size: 13px;
  color: #777;
}

/*============ End Blog Single Styles  =============*/
/**************** blog part css start ****************/
/* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part {
  margin-bottom: 140px;
}

@media (max-width: 576px) {
  /* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part {
    margin-bottom: 0px;
    padding: 0px 0px 70px;
  }
}

@media only screen and (min-width: 576px) and (max-width: 767px) {
  /* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part {
    margin-bottom: 0px;
    padding: 0px 0px 70px;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  /* line 2, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part {
    margin-bottom: 0px;
    padding: 0px 0px 70px;
  }
}

/* line 19, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .blog_right_sidebar .widget_title {
  font-size: 20px;
  margin-bottom: 40px;
  font-style: inherit !important;
}

@media (max-width: 576px) {
  /* line 24, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog {
    margin-bottom: 140px;
    margin-top: 20px;
  }
}

@media only screen and (min-width: 576px) and (max-width: 767px) {
  /* line 24, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog {
    margin-bottom: 140px;
    margin-top: 20px;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  /* line 24, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog {
    margin-bottom: 140px;
    margin-top: 20px;
  }
}

/* line 40, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card-img-top {
  border-radius: 0px;
}

/* line 43, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card {
  border: 0px solid transparent;
  border-radius: 0px;
  background-color: transparent;
  position: relative;
}

/* line 48, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card .card-body {
  padding: 25px 10px 29px 40px;
  background-color: #fff;
  position: absolute;
  left: 20px;
  bottom: -140px;
  box-shadow: -7.552px 9.326px 20px 0px rgba(1, 84, 85, 0.1);
  border-radius: 10px;
}

@media (max-width: 576px) {
  /* line 48, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card .card-body {
    padding: 15px;
    left: 10px;
    bottom: -140px;
  }
}

@media only screen and (min-width: 576px) and (max-width: 767px) {
  /* line 48, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card .card-body {
    padding: 15px;
    left: 10px;
    bottom: -140px;
  }
}

@media only screen and (min-width: 992px) and (max-width: 1200px) {
  /* line 48, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card .card-body {
    padding: 20px;
  }
}

/* line 72, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card .card-body a {
  color: #DB9A64;
  text-transform: uppercase;
  -webkit-transition: 0.8s;
  transition: 0.8s;
}

/* line 76, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card .card-body a:hover {
  background: -webkit-linear-gradient(131deg, #ff7e5f 0%, #feb47b 99%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* line 83, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card .dot {
  position: relative;
  padding-left: 20px;
}

/* line 86, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card .dot:after {
  position: absolute;
  content: "";
  width: 10px;
  height: 10px;
  top: 5px;
  left: 0;
  background-color: #DB9A64;
  border-radius: 50%;
}

/* line 97, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card span {
  color: #8a8a8a;
  margin-bottom: 10px;
  display: inline-block;
  margin-top: 10px;
}

@media (max-width: 576px) {
  /* line 97, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card span {
    margin-bottom: 5px;
    margin-top: 5px;
  }
}

@media only screen and (min-width: 576px) and (max-width: 767px) {
  /* line 97, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card span {
    margin-bottom: 5px;
    margin-top: 5px;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  /* line 97, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card span {
    margin-bottom: 5px;
    margin-top: 5px;
  }
}

@media only screen and (min-width: 992px) and (max-width: 1200px) {
  /* line 97, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card span {
    margin-bottom: 5px;
    margin-top: 5px;
  }
}

/* line 119, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card h5 {
  font-weight: 600;
  line-height: 1.5;
  font-size: 20px;
  -webkit-transition: 0.8s;
  transition: 0.8s;
  text-transform: capitalize;
  margin-bottom: 22px;
}

@media (max-width: 576px) {
  /* line 119, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card h5 {
    margin-bottom: 10px;
  }
}

@media only screen and (min-width: 576px) and (max-width: 767px) {
  /* line 119, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card h5 {
    margin-bottom: 10px;
    font-size: 16px;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  /* line 119, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card h5 {
    margin-bottom: 10px;
  }
}

@media only screen and (min-width: 992px) and (max-width: 1200px) {
  /* line 119, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card h5 {
    margin-bottom: 10px;
    font-size: 18px;
  }
}

/* line 140, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card h5:hover {
  -webkit-transition: 0.8s;
  transition: 0.8s;
  background: -webkit-linear-gradient(131deg, #feb47b 0%, #ff7e5f 99%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-animation: 1s;
}

/* line 150, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card ul li {
  display: inline-block;
  color: #8a8a8a;
  margin-right: 14px;
}

@media (max-width: 576px) {
  /* line 150, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card ul li {
    margin-right: 10px;
  }
}

@media only screen and (min-width: 576px) and (max-width: 767px) {
  /* line 150, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card ul li {
    margin-right: 10px;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  /* line 150, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card ul li {
    margin-right: 10px;
  }
}

@media only screen and (min-width: 992px) and (max-width: 1200px) {
  /* line 150, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
  .blog_part .single-home-blog .card ul li {
    margin-right: 10px;
  }
}

/* line 166, ../../Arafath/CL/Cl November/228. Resume-02/HTML/scss/_blog_part.scss */
.blog_part .single-home-blog .card ul li span {
  margin-right: 10px;
  font-size: 12px;
}

/*# sourceMappingURL=style.css.map */
 </style>
    <style>/*!
        * Bootstrap v4.0.0 (https://getbootstrap.com)
        * Copyright 2011-2018 The Bootstrap Authors
        * Copyright 2011-2018 Twitter, Inc.
        * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
        */
       
       :root {
           --blue: #007bff;
           --indigo: #6610f2;
           --purple: #6f42c1;
           --pink: #e83e8c;
           --red: #dc3545;
           --orange: #fd7e14;
           --yellow: #ffc107;
           --green: #28a745;
           --teal: #20c997;
           --cyan: #17a2b8;
           --white: #fff;
           --gray: #6c757d;
           --gray-dark: #343a40;
           --primary: #007bff;
           --secondary: #6c757d;
           --success: #28a745;
           --info: #17a2b8;
           --warning: #ffc107;
           --danger: #dc3545;
           --light: #f8f9fa;
           --dark: #343a40;
           --breakpoint-xs: 0;
           --breakpoint-sm: 576px;
           --breakpoint-md: 768px;
           --breakpoint-lg: 992px;
           --breakpoint-xl: 1200px;
           --font-family-sans-serif: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
           --font-family-monospace: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace
       }
       
       *,
       ::after,
       ::before {
           box-sizing: border-box
       }
       
       html {
           font-family: sans-serif;
           line-height: 1.15;
           -webkit-text-size-adjust: 100%;
           -ms-text-size-adjust: 100%;
           -ms-overflow-style: scrollbar;
           -webkit-tap-highlight-color: transparent
       }
       
       @-ms-viewport {
           width: device-width
       }
       
       article,
       aside,
       dialog,
       figcaption,
       figure,
       footer,
       header,
       hgroup,
       main,
       nav,
       section {
           display: block
       }
       
       body {
           margin: 0;
           font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
           font-size: 1rem;
           font-weight: 400;
           line-height: 1.5;
           color: #212529;
           text-align: left;
           background-color: #fff
       }
       
       [tabindex="-1"]:focus {
           outline: 0!important
       }
       
       hr {
           box-sizing: content-box;
           height: 0;
           overflow: visible
       }
       
       h1,
       h2,
       h3,
       h4,
       h5,
       h6 {
           margin-top: 0;
           margin-bottom: .5rem
       }
       
       p {
           margin-top: 0;
           margin-bottom: 1rem
       }
       
       abbr[data-original-title],
       abbr[title] {
           text-decoration: underline;
           -webkit-text-decoration: underline dotted;
           text-decoration: underline dotted;
           cursor: help;
           border-bottom: 0
       }
       
       address {
           margin-bottom: 1rem;
           font-style: normal;
           line-height: inherit
       }
       
       dl,
       ol,
       ul {
           margin-top: 0;
           margin-bottom: 1rem
       }
       
       ol ol,
       ol ul,
       ul ol,
       ul ul {
           margin-bottom: 0
       }
       
       dt {
           font-weight: 700
       }
       
       dd {
           margin-bottom: .5rem;
           margin-left: 0
       }
       
       blockquote {
           margin: 0 0 1rem
       }
       
       dfn {
           font-style: italic
       }
       
       b,
       strong {
           font-weight: bolder
       }
       
       small {
           font-size: 80%
       }
       
       sub,
       sup {
           position: relative;
           font-size: 75%;
           line-height: 0;
           vertical-align: baseline
       }
       
       sub {
           bottom: -.25em
       }
       
       sup {
           top: -.5em
       }
       
       a {
           color: #007bff;
           text-decoration: none;
           background-color: transparent;
           -webkit-text-decoration-skip: objects
       }
       
       a:hover {
           color: #0056b3;
           text-decoration: underline
       }
       
       a:not([href]):not([tabindex]) {
           color: inherit;
           text-decoration: none
       }
       
       a:not([href]):not([tabindex]):focus,
       a:not([href]):not([tabindex]):hover {
           color: inherit;
           text-decoration: none
       }
       
       a:not([href]):not([tabindex]):focus {
           outline: 0
       }
       
       code,
       kbd,
       pre,
       samp {
           font-family: monospace, monospace;
           font-size: 1em
       }
       
       pre {
           margin-top: 0;
           margin-bottom: 1rem;
           overflow: auto;
           -ms-overflow-style: scrollbar
       }
       
       figure {
           margin: 0 0 1rem
       }
       
       img {
           vertical-align: middle;
           border-style: none
       }
       
       svg:not(:root) {
           overflow: hidden
       }
       
       table {
           border-collapse: collapse
       }
       
       caption {
           padding-top: .75rem;
           padding-bottom: .75rem;
           color: #6c757d;
           text-align: left;
           caption-side: bottom
       }
       
       th {
           text-align: inherit
       }
       
       label {
           display: inline-block;
           margin-bottom: .5rem
       }
       
       button {
           border-radius: 0
       }
       
       button:focus {
           outline: 1px dotted;
           outline: 5px auto -webkit-focus-ring-color
       }
       
       button,
       input,
       optgroup,
       select,
       textarea {
           margin: 0;
           font-family: inherit;
           font-size: inherit;
           line-height: inherit
       }
       
       button,
       input {
           overflow: visible
       }
       
       button,
       select {
           text-transform: none
       }
       
       [type=reset],
       [type=submit],
       button,
       html [type=button] {
           -webkit-appearance: button
       }
       
       [type=button]::-moz-focus-inner,
       [type=reset]::-moz-focus-inner,
       [type=submit]::-moz-focus-inner,
       button::-moz-focus-inner {
           padding: 0;
           border-style: none
       }
       
       input[type=checkbox],
       input[type=radio] {
           box-sizing: border-box;
           padding: 0
       }
       
       input[type=date],
       input[type=datetime-local],
       input[type=month],
       input[type=time] {
           -webkit-appearance: listbox
       }
       
       textarea {
           overflow: auto;
           resize: vertical
       }
       
       fieldset {
           min-width: 0;
           padding: 0;
           margin: 0;
           border: 0
       }
       
       legend {
           display: block;
           width: 100%;
           max-width: 100%;
           padding: 0;
           margin-bottom: .5rem;
           font-size: 1.5rem;
           line-height: inherit;
           color: inherit;
           white-space: normal
       }
       
       progress {
           vertical-align: baseline
       }
       
       [type=number]::-webkit-inner-spin-button,
       [type=number]::-webkit-outer-spin-button {
           height: auto
       }
       
       [type=search] {
           outline-offset: -2px;
           -webkit-appearance: none
       }
       
       [type=search]::-webkit-search-cancel-button,
       [type=search]::-webkit-search-decoration {
           -webkit-appearance: none
       }
       
       ::-webkit-file-upload-button {
           font: inherit;
           -webkit-appearance: button
       }
       
       output {
           display: inline-block
       }
       
       summary {
           display: list-item;
           cursor: pointer
       }
       
       template {
           display: none
       }
       
       [hidden] {
           display: none!important
       }
       
       .h1,
       .h2,
       .h3,
       .h4,
       .h5,
       .h6,
       h1,
       h2,
       h3,
       h4,
       h5,
       h6 {
           margin-bottom: .5rem;
           font-family: inherit;
           font-weight: 500;
           line-height: 1.2;
           color: inherit
       }
       
       .h1,
       h1 {
           font-size: 2.5rem
       }
       
       .h2,
       h2 {
           font-size: 2rem
       }
       
       .h3,
       h3 {
           font-size: 1.75rem
       }
       
       .h4,
       h4 {
           font-size: 1.5rem
       }
       
       .h5,
       h5 {
           font-size: 1.25rem
       }
       
       .h6,
       h6 {
           font-size: 1rem
       }
       
       .lead {
           font-size: 1.25rem;
           font-weight: 300
       }
       
       .display-1 {
           font-size: 6rem;
           font-weight: 300;
           line-height: 1.2
       }
       
       .display-2 {
           font-size: 5.5rem;
           font-weight: 300;
           line-height: 1.2
       }
       
       .display-3 {
           font-size: 4.5rem;
           font-weight: 300;
           line-height: 1.2
       }
       
       .display-4 {
           font-size: 3.5rem;
           font-weight: 300;
           line-height: 1.2
       }
       
       hr {
           margin-top: 1rem;
           margin-bottom: 1rem;
           border: 0;
           border-top: 1px solid rgba(0, 0, 0, .1)
       }
       
       .small,
       small {
           font-size: 80%;
           font-weight: 400
       }
       
       .mark,
       mark {
           padding: .2em;
           background-color: #fcf8e3
       }
       
       .list-unstyled {
           padding-left: 0;
           list-style: none
       }
       
       .list-inline {
           padding-left: 0;
           list-style: none
       }
       
       .list-inline-item {
           display: inline-block
       }
       
       .list-inline-item:not(:last-child) {
           margin-right: .5rem
       }
       
       .initialism {
           font-size: 90%;
           text-transform: uppercase
       }
       
       .blockquote {
           margin-bottom: 1rem;
           font-size: 1.25rem
       }
       
       .blockquote-footer {
           display: block;
           font-size: 80%;
           color: #6c757d
       }
       
       .blockquote-footer::before {
           content: "\2014 \00A0"
       }
       
       .img-fluid {
           max-width: 100%;
           height: auto
       }
       
       .img-thumbnail {
           padding: .25rem;
           background-color: #fff;
           border: 1px solid #dee2e6;
           border-radius: .25rem;
           max-width: 100%;
           height: auto
       }
       
       .figure {
           display: inline-block
       }
       
       .figure-img {
           margin-bottom: .5rem;
           line-height: 1
       }
       
       .figure-caption {
           font-size: 90%;
           color: #6c757d
       }
       
       code,
       kbd,
       pre,
       samp {
           font-family: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace
       }
       
       code {
           font-size: 87.5%;
           color: #e83e8c;
           word-break: break-word
       }
       
       a>code {
           color: inherit
       }
       
       kbd {
           padding: .2rem .4rem;
           font-size: 87.5%;
           color: #fff;
           background-color: #212529;
           border-radius: .2rem
       }
       
       kbd kbd {
           padding: 0;
           font-size: 100%;
           font-weight: 700
       }
       
       pre {
           display: block;
           font-size: 87.5%;
           color: #212529
       }
       
       pre code {
           font-size: inherit;
           color: inherit;
           word-break: normal
       }
       
       .pre-scrollable {
           max-height: 340px;
           overflow-y: scroll
       }
       
       .container {
           width: 100%;
           padding-right: 15px;
           padding-left: 15px;
           margin-right: auto;
           margin-left: auto
       }
       
       @media (min-width:576px) {
           .container {
               max-width: 540px
           }
       }
       
       @media (min-width:768px) {
           .container {
               max-width: 720px
           }
       }
       
       @media (min-width:992px) {
           .container {
               max-width: 960px
           }
       }
       
       @media (min-width:1200px) {
           .container {
               max-width: 1140px
           }
       }
       
       .container-fluid {
           width: 100%;
           padding-right: 15px;
           padding-left: 15px;
           margin-right: auto;
           margin-left: auto
       }
       
       .row {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           margin-right: -15px;
           margin-left: -15px
       }
       
       .no-gutters {
           margin-right: 0;
           margin-left: 0
       }
       
       .no-gutters>.col,
       .no-gutters>[class*=col-] {
           padding-right: 0;
           padding-left: 0
       }
       
       .col,
       .col-1,
       .col-10,
       .col-11,
       .col-12,
       .col-2,
       .col-3,
       .col-4,
       .col-5,
       .col-6,
       .col-7,
       .col-8,
       .col-9,
       .col-auto,
       .col-lg,
       .col-lg-1,
       .col-lg-10,
       .col-lg-11,
       .col-lg-12,
       .col-lg-2,
       .col-lg-3,
       .col-lg-4,
       .col-lg-5,
       .col-lg-6,
       .col-lg-7,
       .col-lg-8,
       .col-lg-9,
       .col-lg-auto,
       .col-md,
       .col-md-1,
       .col-md-10,
       .col-md-11,
       .col-md-12,
       .col-md-2,
       .col-md-3,
       .col-md-4,
       .col-md-5,
       .col-md-6,
       .col-md-7,
       .col-md-8,
       .col-md-9,
       .col-md-auto,
       .col-sm,
       .col-sm-1,
       .col-sm-10,
       .col-sm-11,
       .col-sm-12,
       .col-sm-2,
       .col-sm-3,
       .col-sm-4,
       .col-sm-5,
       .col-sm-6,
       .col-sm-7,
       .col-sm-8,
       .col-sm-9,
       .col-sm-auto,
       .col-xl,
       .col-xl-1,
       .col-xl-10,
       .col-xl-11,
       .col-xl-12,
       .col-xl-2,
       .col-xl-3,
       .col-xl-4,
       .col-xl-5,
       .col-xl-6,
       .col-xl-7,
       .col-xl-8,
       .col-xl-9,
       .col-xl-auto {
           position: relative;
           width: 100%;
           min-height: 1px;
           padding-right: 15px;
           padding-left: 15px
       }
       
       .col {
           -ms-flex-preferred-size: 0;
           flex-basis: 0;
           -webkit-box-flex: 1;
           -ms-flex-positive: 1;
           flex-grow: 1;
           max-width: 100%
       }
       
       .col-auto {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 auto;
           flex: 0 0 auto;
           width: auto;
           max-width: none
       }
       
       .col-1 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 8.333333%;
           flex: 0 0 8.333333%;
           max-width: 8.333333%
       }
       
       .col-2 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 16.666667%;
           flex: 0 0 16.666667%;
           max-width: 16.666667%
       }
       
       .col-3 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 25%;
           flex: 0 0 25%;
           max-width: 25%
       }
       
       .col-4 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 33.333333%;
           flex: 0 0 33.333333%;
           max-width: 33.333333%
       }
       
       .col-5 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 41.666667%;
           flex: 0 0 41.666667%;
           max-width: 41.666667%
       }
       
       .col-6 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 50%;
           flex: 0 0 50%;
           max-width: 50%
       }
       
       .col-7 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 58.333333%;
           flex: 0 0 58.333333%;
           max-width: 58.333333%
       }
       
       .col-8 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 66.666667%;
           flex: 0 0 66.666667%;
           max-width: 66.666667%
       }
       
       .col-9 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 75%;
           flex: 0 0 75%;
           max-width: 75%
       }
       
       .col-10 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 83.333333%;
           flex: 0 0 83.333333%;
           max-width: 83.333333%
       }
       
       .col-11 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 91.666667%;
           flex: 0 0 91.666667%;
           max-width: 91.666667%
       }
       
       .col-12 {
           -webkit-box-flex: 0;
           -ms-flex: 0 0 100%;
           flex: 0 0 100%;
           max-width: 100%
       }
       
       .order-first {
           -webkit-box-ordinal-group: 0;
           -ms-flex-order: -1;
           order: -1
       }
       
       .order-last {
           -webkit-box-ordinal-group: 14;
           -ms-flex-order: 13;
           order: 13
       }
       
       .order-0 {
           -webkit-box-ordinal-group: 1;
           -ms-flex-order: 0;
           order: 0
       }
       
       .order-1 {
           -webkit-box-ordinal-group: 2;
           -ms-flex-order: 1;
           order: 1
       }
       
       .order-2 {
           -webkit-box-ordinal-group: 3;
           -ms-flex-order: 2;
           order: 2
       }
       
       .order-3 {
           -webkit-box-ordinal-group: 4;
           -ms-flex-order: 3;
           order: 3
       }
       
       .order-4 {
           -webkit-box-ordinal-group: 5;
           -ms-flex-order: 4;
           order: 4
       }
       
       .order-5 {
           -webkit-box-ordinal-group: 6;
           -ms-flex-order: 5;
           order: 5
       }
       
       .order-6 {
           -webkit-box-ordinal-group: 7;
           -ms-flex-order: 6;
           order: 6
       }
       
       .order-7 {
           -webkit-box-ordinal-group: 8;
           -ms-flex-order: 7;
           order: 7
       }
       
       .order-8 {
           -webkit-box-ordinal-group: 9;
           -ms-flex-order: 8;
           order: 8
       }
       
       .order-9 {
           -webkit-box-ordinal-group: 10;
           -ms-flex-order: 9;
           order: 9
       }
       
       .order-10 {
           -webkit-box-ordinal-group: 11;
           -ms-flex-order: 10;
           order: 10
       }
       
       .order-11 {
           -webkit-box-ordinal-group: 12;
           -ms-flex-order: 11;
           order: 11
       }
       
       .order-12 {
           -webkit-box-ordinal-group: 13;
           -ms-flex-order: 12;
           order: 12
       }
       
       .offset-1 {
           margin-left: 8.333333%
       }
       
       .offset-2 {
           margin-left: 16.666667%
       }
       
       .offset-3 {
           margin-left: 25%
       }
       
       .offset-4 {
           margin-left: 33.333333%
       }
       
       .offset-5 {
           margin-left: 41.666667%
       }
       
       .offset-6 {
           margin-left: 50%
       }
       
       .offset-7 {
           margin-left: 58.333333%
       }
       
       .offset-8 {
           margin-left: 66.666667%
       }
       
       .offset-9 {
           margin-left: 75%
       }
       
       .offset-10 {
           margin-left: 83.333333%
       }
       
       .offset-11 {
           margin-left: 91.666667%
       }
       
       @media (min-width:576px) {
           .col-sm {
               -ms-flex-preferred-size: 0;
               flex-basis: 0;
               -webkit-box-flex: 1;
               -ms-flex-positive: 1;
               flex-grow: 1;
               max-width: 100%
           }
           .col-sm-auto {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 auto;
               flex: 0 0 auto;
               width: auto;
               max-width: none
           }
           .col-sm-1 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 8.333333%;
               flex: 0 0 8.333333%;
               max-width: 8.333333%
           }
           .col-sm-2 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 16.666667%;
               flex: 0 0 16.666667%;
               max-width: 16.666667%
           }
           .col-sm-3 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 25%;
               flex: 0 0 25%;
               max-width: 25%
           }
           .col-sm-4 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 33.333333%;
               flex: 0 0 33.333333%;
               max-width: 33.333333%
           }
           .col-sm-5 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 41.666667%;
               flex: 0 0 41.666667%;
               max-width: 41.666667%
           }
           .col-sm-6 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 50%;
               flex: 0 0 50%;
               max-width: 50%
           }
           .col-sm-7 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 58.333333%;
               flex: 0 0 58.333333%;
               max-width: 58.333333%
           }
           .col-sm-8 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 66.666667%;
               flex: 0 0 66.666667%;
               max-width: 66.666667%
           }
           .col-sm-9 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 75%;
               flex: 0 0 75%;
               max-width: 75%
           }
           .col-sm-10 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 83.333333%;
               flex: 0 0 83.333333%;
               max-width: 83.333333%
           }
           .col-sm-11 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 91.666667%;
               flex: 0 0 91.666667%;
               max-width: 91.666667%
           }
           .col-sm-12 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 100%;
               flex: 0 0 100%;
               max-width: 100%
           }
           .order-sm-first {
               -webkit-box-ordinal-group: 0;
               -ms-flex-order: -1;
               order: -1
           }
           .order-sm-last {
               -webkit-box-ordinal-group: 14;
               -ms-flex-order: 13;
               order: 13
           }
           .order-sm-0 {
               -webkit-box-ordinal-group: 1;
               -ms-flex-order: 0;
               order: 0
           }
           .order-sm-1 {
               -webkit-box-ordinal-group: 2;
               -ms-flex-order: 1;
               order: 1
           }
           .order-sm-2 {
               -webkit-box-ordinal-group: 3;
               -ms-flex-order: 2;
               order: 2
           }
           .order-sm-3 {
               -webkit-box-ordinal-group: 4;
               -ms-flex-order: 3;
               order: 3
           }
           .order-sm-4 {
               -webkit-box-ordinal-group: 5;
               -ms-flex-order: 4;
               order: 4
           }
           .order-sm-5 {
               -webkit-box-ordinal-group: 6;
               -ms-flex-order: 5;
               order: 5
           }
           .order-sm-6 {
               -webkit-box-ordinal-group: 7;
               -ms-flex-order: 6;
               order: 6
           }
           .order-sm-7 {
               -webkit-box-ordinal-group: 8;
               -ms-flex-order: 7;
               order: 7
           }
           .order-sm-8 {
               -webkit-box-ordinal-group: 9;
               -ms-flex-order: 8;
               order: 8
           }
           .order-sm-9 {
               -webkit-box-ordinal-group: 10;
               -ms-flex-order: 9;
               order: 9
           }
           .order-sm-10 {
               -webkit-box-ordinal-group: 11;
               -ms-flex-order: 10;
               order: 10
           }
           .order-sm-11 {
               -webkit-box-ordinal-group: 12;
               -ms-flex-order: 11;
               order: 11
           }
           .order-sm-12 {
               -webkit-box-ordinal-group: 13;
               -ms-flex-order: 12;
               order: 12
           }
           .offset-sm-0 {
               margin-left: 0
           }
           .offset-sm-1 {
               margin-left: 8.333333%
           }
           .offset-sm-2 {
               margin-left: 16.666667%
           }
           .offset-sm-3 {
               margin-left: 25%
           }
           .offset-sm-4 {
               margin-left: 33.333333%
           }
           .offset-sm-5 {
               margin-left: 41.666667%
           }
           .offset-sm-6 {
               margin-left: 50%
           }
           .offset-sm-7 {
               margin-left: 58.333333%
           }
           .offset-sm-8 {
               margin-left: 66.666667%
           }
           .offset-sm-9 {
               margin-left: 75%
           }
           .offset-sm-10 {
               margin-left: 83.333333%
           }
           .offset-sm-11 {
               margin-left: 91.666667%
           }
       }
       
       @media (min-width:768px) {
           .col-md {
               -ms-flex-preferred-size: 0;
               flex-basis: 0;
               -webkit-box-flex: 1;
               -ms-flex-positive: 1;
               flex-grow: 1;
               max-width: 100%
           }
           .col-md-auto {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 auto;
               flex: 0 0 auto;
               width: auto;
               max-width: none
           }
           .col-md-1 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 8.333333%;
               flex: 0 0 8.333333%;
               max-width: 8.333333%
           }
           .col-md-2 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 16.666667%;
               flex: 0 0 16.666667%;
               max-width: 16.666667%
           }
           .col-md-3 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 25%;
               flex: 0 0 25%;
               max-width: 25%
           }
           .col-md-4 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 33.333333%;
               flex: 0 0 33.333333%;
               max-width: 33.333333%
           }
           .col-md-5 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 41.666667%;
               flex: 0 0 41.666667%;
               max-width: 41.666667%
           }
           .col-md-6 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 50%;
               flex: 0 0 50%;
               max-width: 50%
           }
           .col-md-7 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 58.333333%;
               flex: 0 0 58.333333%;
               max-width: 58.333333%
           }
           .col-md-8 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 66.666667%;
               flex: 0 0 66.666667%;
               max-width: 66.666667%
           }
           .col-md-9 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 75%;
               flex: 0 0 75%;
               max-width: 75%
           }
           .col-md-10 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 83.333333%;
               flex: 0 0 83.333333%;
               max-width: 83.333333%
           }
           .col-md-11 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 91.666667%;
               flex: 0 0 91.666667%;
               max-width: 91.666667%
           }
           .col-md-12 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 100%;
               flex: 0 0 100%;
               max-width: 100%
           }
           .order-md-first {
               -webkit-box-ordinal-group: 0;
               -ms-flex-order: -1;
               order: -1
           }
           .order-md-last {
               -webkit-box-ordinal-group: 14;
               -ms-flex-order: 13;
               order: 13
           }
           .order-md-0 {
               -webkit-box-ordinal-group: 1;
               -ms-flex-order: 0;
               order: 0
           }
           .order-md-1 {
               -webkit-box-ordinal-group: 2;
               -ms-flex-order: 1;
               order: 1
           }
           .order-md-2 {
               -webkit-box-ordinal-group: 3;
               -ms-flex-order: 2;
               order: 2
           }
           .order-md-3 {
               -webkit-box-ordinal-group: 4;
               -ms-flex-order: 3;
               order: 3
           }
           .order-md-4 {
               -webkit-box-ordinal-group: 5;
               -ms-flex-order: 4;
               order: 4
           }
           .order-md-5 {
               -webkit-box-ordinal-group: 6;
               -ms-flex-order: 5;
               order: 5
           }
           .order-md-6 {
               -webkit-box-ordinal-group: 7;
               -ms-flex-order: 6;
               order: 6
           }
           .order-md-7 {
               -webkit-box-ordinal-group: 8;
               -ms-flex-order: 7;
               order: 7
           }
           .order-md-8 {
               -webkit-box-ordinal-group: 9;
               -ms-flex-order: 8;
               order: 8
           }
           .order-md-9 {
               -webkit-box-ordinal-group: 10;
               -ms-flex-order: 9;
               order: 9
           }
           .order-md-10 {
               -webkit-box-ordinal-group: 11;
               -ms-flex-order: 10;
               order: 10
           }
           .order-md-11 {
               -webkit-box-ordinal-group: 12;
               -ms-flex-order: 11;
               order: 11
           }
           .order-md-12 {
               -webkit-box-ordinal-group: 13;
               -ms-flex-order: 12;
               order: 12
           }
           .offset-md-0 {
               margin-left: 0
           }
           .offset-md-1 {
               margin-left: 8.333333%
           }
           .offset-md-2 {
               margin-left: 16.666667%
           }
           .offset-md-3 {
               margin-left: 25%
           }
           .offset-md-4 {
               margin-left: 33.333333%
           }
           .offset-md-5 {
               margin-left: 41.666667%
           }
           .offset-md-6 {
               margin-left: 50%
           }
           .offset-md-7 {
               margin-left: 58.333333%
           }
           .offset-md-8 {
               margin-left: 66.666667%
           }
           .offset-md-9 {
               margin-left: 75%
           }
           .offset-md-10 {
               margin-left: 83.333333%
           }
           .offset-md-11 {
               margin-left: 91.666667%
           }
       }
       
       @media (min-width:992px) {
           .col-lg {
               -ms-flex-preferred-size: 0;
               flex-basis: 0;
               -webkit-box-flex: 1;
               -ms-flex-positive: 1;
               flex-grow: 1;
               max-width: 100%
           }
           .col-lg-auto {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 auto;
               flex: 0 0 auto;
               width: auto;
               max-width: none
           }
           .col-lg-1 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 8.333333%;
               flex: 0 0 8.333333%;
               max-width: 8.333333%
           }
           .col-lg-2 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 16.666667%;
               flex: 0 0 16.666667%;
               max-width: 16.666667%
           }
           .col-lg-3 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 25%;
               flex: 0 0 25%;
               max-width: 25%
           }
           .col-lg-4 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 33.333333%;
               flex: 0 0 33.333333%;
               max-width: 33.333333%
           }
           .col-lg-5 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 41.666667%;
               flex: 0 0 41.666667%;
               max-width: 41.666667%
           }
           .col-lg-6 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 50%;
               flex: 0 0 50%;
               max-width: 50%
           }
           .col-lg-7 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 58.333333%;
               flex: 0 0 58.333333%;
               max-width: 58.333333%
           }
           .col-lg-8 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 66.666667%;
               flex: 0 0 66.666667%;
               max-width: 66.666667%
           }
           .col-lg-9 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 75%;
               flex: 0 0 75%;
               max-width: 75%
           }
           .col-lg-10 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 83.333333%;
               flex: 0 0 83.333333%;
               max-width: 83.333333%
           }
           .col-lg-11 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 91.666667%;
               flex: 0 0 91.666667%;
               max-width: 91.666667%
           }
           .col-lg-12 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 100%;
               flex: 0 0 100%;
               max-width: 100%
           }
           .order-lg-first {
               -webkit-box-ordinal-group: 0;
               -ms-flex-order: -1;
               order: -1
           }
           .order-lg-last {
               -webkit-box-ordinal-group: 14;
               -ms-flex-order: 13;
               order: 13
           }
           .order-lg-0 {
               -webkit-box-ordinal-group: 1;
               -ms-flex-order: 0;
               order: 0
           }
           .order-lg-1 {
               -webkit-box-ordinal-group: 2;
               -ms-flex-order: 1;
               order: 1
           }
           .order-lg-2 {
               -webkit-box-ordinal-group: 3;
               -ms-flex-order: 2;
               order: 2
           }
           .order-lg-3 {
               -webkit-box-ordinal-group: 4;
               -ms-flex-order: 3;
               order: 3
           }
           .order-lg-4 {
               -webkit-box-ordinal-group: 5;
               -ms-flex-order: 4;
               order: 4
           }
           .order-lg-5 {
               -webkit-box-ordinal-group: 6;
               -ms-flex-order: 5;
               order: 5
           }
           .order-lg-6 {
               -webkit-box-ordinal-group: 7;
               -ms-flex-order: 6;
               order: 6
           }
           .order-lg-7 {
               -webkit-box-ordinal-group: 8;
               -ms-flex-order: 7;
               order: 7
           }
           .order-lg-8 {
               -webkit-box-ordinal-group: 9;
               -ms-flex-order: 8;
               order: 8
           }
           .order-lg-9 {
               -webkit-box-ordinal-group: 10;
               -ms-flex-order: 9;
               order: 9
           }
           .order-lg-10 {
               -webkit-box-ordinal-group: 11;
               -ms-flex-order: 10;
               order: 10
           }
           .order-lg-11 {
               -webkit-box-ordinal-group: 12;
               -ms-flex-order: 11;
               order: 11
           }
           .order-lg-12 {
               -webkit-box-ordinal-group: 13;
               -ms-flex-order: 12;
               order: 12
           }
           .offset-lg-0 {
               margin-left: 0
           }
           .offset-lg-1 {
               margin-left: 8.333333%
           }
           .offset-lg-2 {
               margin-left: 16.666667%
           }
           .offset-lg-3 {
               margin-left: 25%
           }
           .offset-lg-4 {
               margin-left: 33.333333%
           }
           .offset-lg-5 {
               margin-left: 41.666667%
           }
           .offset-lg-6 {
               margin-left: 50%
           }
           .offset-lg-7 {
               margin-left: 58.333333%
           }
           .offset-lg-8 {
               margin-left: 66.666667%
           }
           .offset-lg-9 {
               margin-left: 75%
           }
           .offset-lg-10 {
               margin-left: 83.333333%
           }
           .offset-lg-11 {
               margin-left: 91.666667%
           }
       }
       
       @media (min-width:1200px) {
           .col-xl {
               -ms-flex-preferred-size: 0;
               flex-basis: 0;
               -webkit-box-flex: 1;
               -ms-flex-positive: 1;
               flex-grow: 1;
               max-width: 100%
           }
           .col-xl-auto {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 auto;
               flex: 0 0 auto;
               width: auto;
               max-width: none
           }
           .col-xl-1 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 8.333333%;
               flex: 0 0 8.333333%;
               max-width: 8.333333%
           }
           .col-xl-2 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 16.666667%;
               flex: 0 0 16.666667%;
               max-width: 16.666667%
           }
           .col-xl-3 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 25%;
               flex: 0 0 25%;
               max-width: 25%
           }
           .col-xl-4 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 33.333333%;
               flex: 0 0 33.333333%;
               max-width: 33.333333%
           }
           .col-xl-5 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 41.666667%;
               flex: 0 0 41.666667%;
               max-width: 41.666667%
           }
           .col-xl-6 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 50%;
               flex: 0 0 50%;
               max-width: 50%
           }
           .col-xl-7 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 58.333333%;
               flex: 0 0 58.333333%;
               max-width: 58.333333%
           }
           .col-xl-8 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 66.666667%;
               flex: 0 0 66.666667%;
               max-width: 66.666667%
           }
           .col-xl-9 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 75%;
               flex: 0 0 75%;
               max-width: 75%
           }
           .col-xl-10 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 83.333333%;
               flex: 0 0 83.333333%;
               max-width: 83.333333%
           }
           .col-xl-11 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 91.666667%;
               flex: 0 0 91.666667%;
               max-width: 91.666667%
           }
           .col-xl-12 {
               -webkit-box-flex: 0;
               -ms-flex: 0 0 100%;
               flex: 0 0 100%;
               max-width: 100%
           }
           .order-xl-first {
               -webkit-box-ordinal-group: 0;
               -ms-flex-order: -1;
               order: -1
           }
           .order-xl-last {
               -webkit-box-ordinal-group: 14;
               -ms-flex-order: 13;
               order: 13
           }
           .order-xl-0 {
               -webkit-box-ordinal-group: 1;
               -ms-flex-order: 0;
               order: 0
           }
           .order-xl-1 {
               -webkit-box-ordinal-group: 2;
               -ms-flex-order: 1;
               order: 1
           }
           .order-xl-2 {
               -webkit-box-ordinal-group: 3;
               -ms-flex-order: 2;
               order: 2
           }
           .order-xl-3 {
               -webkit-box-ordinal-group: 4;
               -ms-flex-order: 3;
               order: 3
           }
           .order-xl-4 {
               -webkit-box-ordinal-group: 5;
               -ms-flex-order: 4;
               order: 4
           }
           .order-xl-5 {
               -webkit-box-ordinal-group: 6;
               -ms-flex-order: 5;
               order: 5
           }
           .order-xl-6 {
               -webkit-box-ordinal-group: 7;
               -ms-flex-order: 6;
               order: 6
           }
           .order-xl-7 {
               -webkit-box-ordinal-group: 8;
               -ms-flex-order: 7;
               order: 7
           }
           .order-xl-8 {
               -webkit-box-ordinal-group: 9;
               -ms-flex-order: 8;
               order: 8
           }
           .order-xl-9 {
               -webkit-box-ordinal-group: 10;
               -ms-flex-order: 9;
               order: 9
           }
           .order-xl-10 {
               -webkit-box-ordinal-group: 11;
               -ms-flex-order: 10;
               order: 10
           }
           .order-xl-11 {
               -webkit-box-ordinal-group: 12;
               -ms-flex-order: 11;
               order: 11
           }
           .order-xl-12 {
               -webkit-box-ordinal-group: 13;
               -ms-flex-order: 12;
               order: 12
           }
           .offset-xl-0 {
               margin-left: 0
           }
           .offset-xl-1 {
               margin-left: 8.333333%
           }
           .offset-xl-2 {
               margin-left: 16.666667%
           }
           .offset-xl-3 {
               margin-left: 25%
           }
           .offset-xl-4 {
               margin-left: 33.333333%
           }
           .offset-xl-5 {
               margin-left: 41.666667%
           }
           .offset-xl-6 {
               margin-left: 50%
           }
           .offset-xl-7 {
               margin-left: 58.333333%
           }
           .offset-xl-8 {
               margin-left: 66.666667%
           }
           .offset-xl-9 {
               margin-left: 75%
           }
           .offset-xl-10 {
               margin-left: 83.333333%
           }
           .offset-xl-11 {
               margin-left: 91.666667%
           }
       }
       
       .table {
           width: 100%;
           max-width: 100%;
           margin-bottom: 1rem;
           background-color: transparent
       }
       
       .table td,
       .table th {
           padding: .75rem;
           vertical-align: top;
           border-top: 1px solid #dee2e6
       }
       
       .table thead th {
           vertical-align: bottom;
           border-bottom: 2px solid #dee2e6
       }
       
       .table tbody+tbody {
           border-top: 2px solid #dee2e6
       }
       
       .table .table {
           background-color: #fff
       }
       
       .table-sm td,
       .table-sm th {
           padding: .3rem
       }
       
       .table-bordered {
           border: 1px solid #dee2e6
       }
       
       .table-bordered td,
       .table-bordered th {
           border: 1px solid #dee2e6
       }
       
       .table-bordered thead td,
       .table-bordered thead th {
           border-bottom-width: 2px
       }
       
       .table-striped tbody tr:nth-of-type(odd) {
           background-color: rgba(0, 0, 0, .05)
       }
       
       .table-hover tbody tr:hover {
           background-color: rgba(0, 0, 0, .075)
       }
       
       .table-primary,
       .table-primary>td,
       .table-primary>th {
           background-color: #b8daff
       }
       
       .table-hover .table-primary:hover {
           background-color: #9fcdff
       }
       
       .table-hover .table-primary:hover>td,
       .table-hover .table-primary:hover>th {
           background-color: #9fcdff
       }
       
       .table-secondary,
       .table-secondary>td,
       .table-secondary>th {
           background-color: #d6d8db
       }
       
       .table-hover .table-secondary:hover {
           background-color: #c8cbcf
       }
       
       .table-hover .table-secondary:hover>td,
       .table-hover .table-secondary:hover>th {
           background-color: #c8cbcf
       }
       
       .table-success,
       .table-success>td,
       .table-success>th {
           background-color: #c3e6cb
       }
       
       .table-hover .table-success:hover {
           background-color: #b1dfbb
       }
       
       .table-hover .table-success:hover>td,
       .table-hover .table-success:hover>th {
           background-color: #b1dfbb
       }
       
       .table-info,
       .table-info>td,
       .table-info>th {
           background-color: #bee5eb
       }
       
       .table-hover .table-info:hover {
           background-color: #abdde5
       }
       
       .table-hover .table-info:hover>td,
       .table-hover .table-info:hover>th {
           background-color: #abdde5
       }
       
       .table-warning,
       .table-warning>td,
       .table-warning>th {
           background-color: #ffeeba
       }
       
       .table-hover .table-warning:hover {
           background-color: #ffe8a1
       }
       
       .table-hover .table-warning:hover>td,
       .table-hover .table-warning:hover>th {
           background-color: #ffe8a1
       }
       
       .table-danger,
       .table-danger>td,
       .table-danger>th {
           background-color: #f5c6cb
       }
       
       .table-hover .table-danger:hover {
           background-color: #f1b0b7
       }
       
       .table-hover .table-danger:hover>td,
       .table-hover .table-danger:hover>th {
           background-color: #f1b0b7
       }
       
       .table-light,
       .table-light>td,
       .table-light>th {
           background-color: #fdfdfe
       }
       
       .table-hover .table-light:hover {
           background-color: #ececf6
       }
       
       .table-hover .table-light:hover>td,
       .table-hover .table-light:hover>th {
           background-color: #ececf6
       }
       
       .table-dark,
       .table-dark>td,
       .table-dark>th {
           background-color: #c6c8ca
       }
       
       .table-hover .table-dark:hover {
           background-color: #b9bbbe
       }
       
       .table-hover .table-dark:hover>td,
       .table-hover .table-dark:hover>th {
           background-color: #b9bbbe
       }
       
       .table-active,
       .table-active>td,
       .table-active>th {
           background-color: rgba(0, 0, 0, .075)
       }
       
       .table-hover .table-active:hover {
           background-color: rgba(0, 0, 0, .075)
       }
       
       .table-hover .table-active:hover>td,
       .table-hover .table-active:hover>th {
           background-color: rgba(0, 0, 0, .075)
       }
       
       .table .thead-dark th {
           color: #fff;
           background-color: #212529;
           border-color: #32383e
       }
       
       .table .thead-light th {
           color: #495057;
           background-color: #e9ecef;
           border-color: #dee2e6
       }
       
       .table-dark {
           color: #fff;
           background-color: #212529
       }
       
       .table-dark td,
       .table-dark th,
       .table-dark thead th {
           border-color: #32383e
       }
       
       .table-dark.table-bordered {
           border: 0
       }
       
       .table-dark.table-striped tbody tr:nth-of-type(odd) {
           background-color: rgba(255, 255, 255, .05)
       }
       
       .table-dark.table-hover tbody tr:hover {
           background-color: rgba(255, 255, 255, .075)
       }
       
       @media (max-width:575.98px) {
           .table-responsive-sm {
               display: block;
               width: 100%;
               overflow-x: auto;
               -webkit-overflow-scrolling: touch;
               -ms-overflow-style: -ms-autohiding-scrollbar
           }
           .table-responsive-sm>.table-bordered {
               border: 0
           }
       }
       
       @media (max-width:767.98px) {
           .table-responsive-md {
               display: block;
               width: 100%;
               overflow-x: auto;
               -webkit-overflow-scrolling: touch;
               -ms-overflow-style: -ms-autohiding-scrollbar
           }
           .table-responsive-md>.table-bordered {
               border: 0
           }
       }
       
       @media (max-width:991.98px) {
           .table-responsive-lg {
               display: block;
               width: 100%;
               overflow-x: auto;
               -webkit-overflow-scrolling: touch;
               -ms-overflow-style: -ms-autohiding-scrollbar
           }
           .table-responsive-lg>.table-bordered {
               border: 0
           }
       }
       
       @media (max-width:1199.98px) {
           .table-responsive-xl {
               display: block;
               width: 100%;
               overflow-x: auto;
               -webkit-overflow-scrolling: touch;
               -ms-overflow-style: -ms-autohiding-scrollbar
           }
           .table-responsive-xl>.table-bordered {
               border: 0
           }
       }
       
       .table-responsive {
           display: block;
           width: 100%;
           overflow-x: auto;
           -webkit-overflow-scrolling: touch;
           -ms-overflow-style: -ms-autohiding-scrollbar
       }
       
       .table-responsive>.table-bordered {
           border: 0
       }
       
       .form-control {
           display: block;
           width: 100%;
           padding: .375rem .75rem;
           font-size: 1rem;
           line-height: 1.5;
           color: #495057;
           background-color: #fff;
           background-clip: padding-box;
           border: 1px solid #ced4da;
           border-radius: .25rem;
           transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out
       }
       
       .form-control::-ms-expand {
           background-color: transparent;
           border: 0
       }
       
       .form-control:focus {
           color: #495057;
           background-color: #fff;
           border-color: #80bdff;
           outline: 0;
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .25)
       }
       
       .form-control::-webkit-input-placeholder {
           color: #6c757d;
           opacity: 1
       }
       
       .form-control::-moz-placeholder {
           color: #6c757d;
           opacity: 1
       }
       
       .form-control:-ms-input-placeholder {
           color: #6c757d;
           opacity: 1
       }
       
       .form-control::-ms-input-placeholder {
           color: #6c757d;
           opacity: 1
       }
       
       .form-control::placeholder {
           color: #6c757d;
           opacity: 1
       }
       
       .form-control:disabled,
       .form-control[readonly] {
           background-color: #e9ecef;
           opacity: 1
       }
       
       select.form-control:not([size]):not([multiple]) {
           height: calc(2.25rem + 2px)
       }
       
       select.form-control:focus::-ms-value {
           color: #495057;
           background-color: #fff
       }
       
       .form-control-file,
       .form-control-range {
           display: block;
           width: 100%
       }
       
       .col-form-label {
           padding-top: calc(.375rem + 1px);
           padding-bottom: calc(.375rem + 1px);
           margin-bottom: 0;
           font-size: inherit;
           line-height: 1.5
       }
       
       .col-form-label-lg {
           padding-top: calc(.5rem + 1px);
           padding-bottom: calc(.5rem + 1px);
           font-size: 1.25rem;
           line-height: 1.5
       }
       
       .col-form-label-sm {
           padding-top: calc(.25rem + 1px);
           padding-bottom: calc(.25rem + 1px);
           font-size: .875rem;
           line-height: 1.5
       }
       
       .form-control-plaintext {
           display: block;
           width: 100%;
           padding-top: .375rem;
           padding-bottom: .375rem;
           margin-bottom: 0;
           line-height: 1.5;
           background-color: transparent;
           border: solid transparent;
           border-width: 1px 0
       }
       
       .form-control-plaintext.form-control-lg,
       .form-control-plaintext.form-control-sm,
       .input-group-lg>.form-control-plaintext.form-control,
       .input-group-lg>.input-group-append>.form-control-plaintext.btn,
       .input-group-lg>.input-group-append>.form-control-plaintext.input-group-text,
       .input-group-lg>.input-group-prepend>.form-control-plaintext.btn,
       .input-group-lg>.input-group-prepend>.form-control-plaintext.input-group-text,
       .input-group-sm>.form-control-plaintext.form-control,
       .input-group-sm>.input-group-append>.form-control-plaintext.btn,
       .input-group-sm>.input-group-append>.form-control-plaintext.input-group-text,
       .input-group-sm>.input-group-prepend>.form-control-plaintext.btn,
       .input-group-sm>.input-group-prepend>.form-control-plaintext.input-group-text {
           padding-right: 0;
           padding-left: 0
       }
       
       .form-control-sm,
       .input-group-sm>.form-control,
       .input-group-sm>.input-group-append>.btn,
       .input-group-sm>.input-group-append>.input-group-text,
       .input-group-sm>.input-group-prepend>.btn,
       .input-group-sm>.input-group-prepend>.input-group-text {
           padding: .25rem .5rem;
           font-size: .875rem;
           line-height: 1.5;
           border-radius: .2rem
       }
       
       .input-group-sm>.input-group-append>select.btn:not([size]):not([multiple]),
       .input-group-sm>.input-group-append>select.input-group-text:not([size]):not([multiple]),
       .input-group-sm>.input-group-prepend>select.btn:not([size]):not([multiple]),
       .input-group-sm>.input-group-prepend>select.input-group-text:not([size]):not([multiple]),
       .input-group-sm>select.form-control:not([size]):not([multiple]),
       select.form-control-sm:not([size]):not([multiple]) {
           height: calc(1.8125rem + 2px)
       }
       
       .form-control-lg,
       .input-group-lg>.form-control,
       .input-group-lg>.input-group-append>.btn,
       .input-group-lg>.input-group-append>.input-group-text,
       .input-group-lg>.input-group-prepend>.btn,
       .input-group-lg>.input-group-prepend>.input-group-text {
           padding: .5rem 1rem;
           font-size: 1.25rem;
           line-height: 1.5;
           border-radius: .3rem
       }
       
       .input-group-lg>.input-group-append>select.btn:not([size]):not([multiple]),
       .input-group-lg>.input-group-append>select.input-group-text:not([size]):not([multiple]),
       .input-group-lg>.input-group-prepend>select.btn:not([size]):not([multiple]),
       .input-group-lg>.input-group-prepend>select.input-group-text:not([size]):not([multiple]),
       .input-group-lg>select.form-control:not([size]):not([multiple]),
       select.form-control-lg:not([size]):not([multiple]) {
           height: calc(2.875rem + 2px)
       }
       
       .form-group {
           margin-bottom: 1rem
       }
       
       .form-text {
           display: block;
           margin-top: .25rem
       }
       
       .form-row {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           margin-right: -5px;
           margin-left: -5px
       }
       
       .form-row>.col,
       .form-row>[class*=col-] {
           padding-right: 5px;
           padding-left: 5px
       }
       
       .form-check {
           position: relative;
           display: block;
           padding-left: 1.25rem
       }
       
       .form-check-input {
           position: absolute;
           margin-top: .3rem;
           margin-left: -1.25rem
       }
       
       .form-check-input:disabled~.form-check-label {
           color: #6c757d
       }
       
       .form-check-label {
           margin-bottom: 0
       }
       
       .form-check-inline {
           display: -webkit-inline-box;
           display: -ms-inline-flexbox;
           display: inline-flex;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           padding-left: 0;
           margin-right: .75rem
       }
       
       .form-check-inline .form-check-input {
           position: static;
           margin-top: 0;
           margin-right: .3125rem;
           margin-left: 0
       }
       
       .valid-feedback {
           display: none;
           width: 100%;
           margin-top: .25rem;
           font-size: 80%;
           color: #28a745
       }
       
       .valid-tooltip {
           position: absolute;
           top: 100%;
           z-index: 5;
           display: none;
           max-width: 100%;
           padding: .5rem;
           margin-top: .1rem;
           font-size: .875rem;
           line-height: 1;
           color: #fff;
           background-color: rgba(40, 167, 69, .8);
           border-radius: .2rem
       }
       
       .custom-select.is-valid,
       .form-control.is-valid,
       .was-validated .custom-select:valid,
       .was-validated .form-control:valid {
           border-color: #28a745
       }
       
       .custom-select.is-valid:focus,
       .form-control.is-valid:focus,
       .was-validated .custom-select:valid:focus,
       .was-validated .form-control:valid:focus {
           border-color: #28a745;
           box-shadow: 0 0 0 .2rem rgba(40, 167, 69, .25)
       }
       
       .custom-select.is-valid~.valid-feedback,
       .custom-select.is-valid~.valid-tooltip,
       .form-control.is-valid~.valid-feedback,
       .form-control.is-valid~.valid-tooltip,
       .was-validated .custom-select:valid~.valid-feedback,
       .was-validated .custom-select:valid~.valid-tooltip,
       .was-validated .form-control:valid~.valid-feedback,
       .was-validated .form-control:valid~.valid-tooltip {
           display: block
       }
       
       .form-check-input.is-valid~.form-check-label,
       .was-validated .form-check-input:valid~.form-check-label {
           color: #28a745
       }
       
       .form-check-input.is-valid~.valid-feedback,
       .form-check-input.is-valid~.valid-tooltip,
       .was-validated .form-check-input:valid~.valid-feedback,
       .was-validated .form-check-input:valid~.valid-tooltip {
           display: block
       }
       
       .custom-control-input.is-valid~.custom-control-label,
       .was-validated .custom-control-input:valid~.custom-control-label {
           color: #28a745
       }
       
       .custom-control-input.is-valid~.custom-control-label::before,
       .was-validated .custom-control-input:valid~.custom-control-label::before {
           background-color: #71dd8a
       }
       
       .custom-control-input.is-valid~.valid-feedback,
       .custom-control-input.is-valid~.valid-tooltip,
       .was-validated .custom-control-input:valid~.valid-feedback,
       .was-validated .custom-control-input:valid~.valid-tooltip {
           display: block
       }
       
       .custom-control-input.is-valid:checked~.custom-control-label::before,
       .was-validated .custom-control-input:valid:checked~.custom-control-label::before {
           background-color: #34ce57
       }
       
       .custom-control-input.is-valid:focus~.custom-control-label::before,
       .was-validated .custom-control-input:valid:focus~.custom-control-label::before {
           box-shadow: 0 0 0 1px #fff, 0 0 0 .2rem rgba(40, 167, 69, .25)
       }
       
       .custom-file-input.is-valid~.custom-file-label,
       .was-validated .custom-file-input:valid~.custom-file-label {
           border-color: #28a745
       }
       
       .custom-file-input.is-valid~.custom-file-label::before,
       .was-validated .custom-file-input:valid~.custom-file-label::before {
           border-color: inherit
       }
       
       .custom-file-input.is-valid~.valid-feedback,
       .custom-file-input.is-valid~.valid-tooltip,
       .was-validated .custom-file-input:valid~.valid-feedback,
       .was-validated .custom-file-input:valid~.valid-tooltip {
           display: block
       }
       
       .custom-file-input.is-valid:focus~.custom-file-label,
       .was-validated .custom-file-input:valid:focus~.custom-file-label {
           box-shadow: 0 0 0 .2rem rgba(40, 167, 69, .25)
       }
       
       .invalid-feedback {
           display: none;
           width: 100%;
           margin-top: .25rem;
           font-size: 80%;
           color: #dc3545
       }
       
       .invalid-tooltip {
           position: absolute;
           top: 100%;
           z-index: 5;
           display: none;
           max-width: 100%;
           padding: .5rem;
           margin-top: .1rem;
           font-size: .875rem;
           line-height: 1;
           color: #fff;
           background-color: rgba(220, 53, 69, .8);
           border-radius: .2rem
       }
       
       .custom-select.is-invalid,
       .form-control.is-invalid,
       .was-validated .custom-select:invalid,
       .was-validated .form-control:invalid {
           border-color: #dc3545
       }
       
       .custom-select.is-invalid:focus,
       .form-control.is-invalid:focus,
       .was-validated .custom-select:invalid:focus,
       .was-validated .form-control:invalid:focus {
           border-color: #dc3545;
           box-shadow: 0 0 0 .2rem rgba(220, 53, 69, .25)
       }
       
       .custom-select.is-invalid~.invalid-feedback,
       .custom-select.is-invalid~.invalid-tooltip,
       .form-control.is-invalid~.invalid-feedback,
       .form-control.is-invalid~.invalid-tooltip,
       .was-validated .custom-select:invalid~.invalid-feedback,
       .was-validated .custom-select:invalid~.invalid-tooltip,
       .was-validated .form-control:invalid~.invalid-feedback,
       .was-validated .form-control:invalid~.invalid-tooltip {
           display: block
       }
       
       .form-check-input.is-invalid~.form-check-label,
       .was-validated .form-check-input:invalid~.form-check-label {
           color: #dc3545
       }
       
       .form-check-input.is-invalid~.invalid-feedback,
       .form-check-input.is-invalid~.invalid-tooltip,
       .was-validated .form-check-input:invalid~.invalid-feedback,
       .was-validated .form-check-input:invalid~.invalid-tooltip {
           display: block
       }
       
       .custom-control-input.is-invalid~.custom-control-label,
       .was-validated .custom-control-input:invalid~.custom-control-label {
           color: #dc3545
       }
       
       .custom-control-input.is-invalid~.custom-control-label::before,
       .was-validated .custom-control-input:invalid~.custom-control-label::before {
           background-color: #efa2a9
       }
       
       .custom-control-input.is-invalid~.invalid-feedback,
       .custom-control-input.is-invalid~.invalid-tooltip,
       .was-validated .custom-control-input:invalid~.invalid-feedback,
       .was-validated .custom-control-input:invalid~.invalid-tooltip {
           display: block
       }
       
       .custom-control-input.is-invalid:checked~.custom-control-label::before,
       .was-validated .custom-control-input:invalid:checked~.custom-control-label::before {
           background-color: #e4606d
       }
       
       .custom-control-input.is-invalid:focus~.custom-control-label::before,
       .was-validated .custom-control-input:invalid:focus~.custom-control-label::before {
           box-shadow: 0 0 0 1px #fff, 0 0 0 .2rem rgba(220, 53, 69, .25)
       }
       
       .custom-file-input.is-invalid~.custom-file-label,
       .was-validated .custom-file-input:invalid~.custom-file-label {
           border-color: #dc3545
       }
       
       .custom-file-input.is-invalid~.custom-file-label::before,
       .was-validated .custom-file-input:invalid~.custom-file-label::before {
           border-color: inherit
       }
       
       .custom-file-input.is-invalid~.invalid-feedback,
       .custom-file-input.is-invalid~.invalid-tooltip,
       .was-validated .custom-file-input:invalid~.invalid-feedback,
       .was-validated .custom-file-input:invalid~.invalid-tooltip {
           display: block
       }
       
       .custom-file-input.is-invalid:focus~.custom-file-label,
       .was-validated .custom-file-input:invalid:focus~.custom-file-label {
           box-shadow: 0 0 0 .2rem rgba(220, 53, 69, .25)
       }
       
       .form-inline {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: horizontal;
           -webkit-box-direction: normal;
           -ms-flex-flow: row wrap;
           flex-flow: row wrap;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center
       }
       
       .form-inline .form-check {
           width: 100%
       }
       
       @media (min-width:576px) {
           .form-inline label {
               display: -webkit-box;
               display: -ms-flexbox;
               display: flex;
               -webkit-box-align: center;
               -ms-flex-align: center;
               align-items: center;
               -webkit-box-pack: center;
               -ms-flex-pack: center;
               justify-content: center;
               margin-bottom: 0
           }
           .form-inline .form-group {
               display: -webkit-box;
               display: -ms-flexbox;
               display: flex;
               -webkit-box-flex: 0;
               -ms-flex: 0 0 auto;
               flex: 0 0 auto;
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-flow: row wrap;
               flex-flow: row wrap;
               -webkit-box-align: center;
               -ms-flex-align: center;
               align-items: center;
               margin-bottom: 0
           }
           .form-inline .form-control {
               display: inline-block;
               width: auto;
               vertical-align: middle
           }
           .form-inline .form-control-plaintext {
               display: inline-block
           }
           .form-inline .input-group {
               width: auto
           }
           .form-inline .form-check {
               display: -webkit-box;
               display: -ms-flexbox;
               display: flex;
               -webkit-box-align: center;
               -ms-flex-align: center;
               align-items: center;
               -webkit-box-pack: center;
               -ms-flex-pack: center;
               justify-content: center;
               width: auto;
               padding-left: 0
           }
           .form-inline .form-check-input {
               position: relative;
               margin-top: 0;
               margin-right: .25rem;
               margin-left: 0
           }
           .form-inline .custom-control {
               -webkit-box-align: center;
               -ms-flex-align: center;
               align-items: center;
               -webkit-box-pack: center;
               -ms-flex-pack: center;
               justify-content: center
           }
           .form-inline .custom-control-label {
               margin-bottom: 0
           }
       }
       
       .btn {
           display: inline-block;
           font-weight: 400;
           text-align: center;
           white-space: nowrap;
           vertical-align: middle;
           -webkit-user-select: none;
           -moz-user-select: none;
           -ms-user-select: none;
           user-select: none;
           border: 1px solid transparent;
           padding: .375rem .75rem;
           font-size: 1rem;
           line-height: 1.5;
           border-radius: .25rem;
           transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out
       }
       
       .btn:focus,
       .btn:hover {
           text-decoration: none
       }
       
       .btn.focus,
       .btn:focus {
           outline: 0;
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .25)
       }
       
       .btn.disabled,
       .btn:disabled {
           opacity: .65
       }
       
       .btn:not(:disabled):not(.disabled) {
           cursor: pointer
       }
       
       .btn:not(:disabled):not(.disabled).active,
       .btn:not(:disabled):not(.disabled):active {
           background-image: none
       }
       
       a.btn.disabled,
       fieldset:disabled a.btn {
           pointer-events: none
       }
       
       .btn-primary {
           color: #fff;
           background-color: #007bff;
           border-color: #007bff
       }
       
       .btn-primary:hover {
           color: #fff;
           background-color: #0069d9;
           border-color: #0062cc
       }
       
       .btn-primary.focus,
       .btn-primary:focus {
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .5)
       }
       
       .btn-primary.disabled,
       .btn-primary:disabled {
           color: #fff;
           background-color: #007bff;
           border-color: #007bff
       }
       
       .btn-primary:not(:disabled):not(.disabled).active,
       .btn-primary:not(:disabled):not(.disabled):active,
       .show>.btn-primary.dropdown-toggle {
           color: #fff;
           background-color: #0062cc;
           border-color: #005cbf
       }
       
       .btn-primary:not(:disabled):not(.disabled).active:focus,
       .btn-primary:not(:disabled):not(.disabled):active:focus,
       .show>.btn-primary.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .5)
       }
       
       .btn-secondary {
           color: #fff;
           background-color: #6c757d;
           border-color: #6c757d
       }
       
       .btn-secondary:hover {
           color: #fff;
           background-color: #5a6268;
           border-color: #545b62
       }
       
       .btn-secondary.focus,
       .btn-secondary:focus {
           box-shadow: 0 0 0 .2rem rgba(108, 117, 125, .5)
       }
       
       .btn-secondary.disabled,
       .btn-secondary:disabled {
           color: #fff;
           background-color: #6c757d;
           border-color: #6c757d
       }
       
       .btn-secondary:not(:disabled):not(.disabled).active,
       .btn-secondary:not(:disabled):not(.disabled):active,
       .show>.btn-secondary.dropdown-toggle {
           color: #fff;
           background-color: #545b62;
           border-color: #4e555b
       }
       
       .btn-secondary:not(:disabled):not(.disabled).active:focus,
       .btn-secondary:not(:disabled):not(.disabled):active:focus,
       .show>.btn-secondary.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(108, 117, 125, .5)
       }
       
       .btn-success {
           color: #fff;
           background-color: #28a745;
           border-color: #28a745
       }
       
       .btn-success:hover {
           color: #fff;
           background-color: #218838;
           border-color: #1e7e34
       }
       
       .btn-success.focus,
       .btn-success:focus {
           box-shadow: 0 0 0 .2rem rgba(40, 167, 69, .5)
       }
       
       .btn-success.disabled,
       .btn-success:disabled {
           color: #fff;
           background-color: #28a745;
           border-color: #28a745
       }
       
       .btn-success:not(:disabled):not(.disabled).active,
       .btn-success:not(:disabled):not(.disabled):active,
       .show>.btn-success.dropdown-toggle {
           color: #fff;
           background-color: #1e7e34;
           border-color: #1c7430
       }
       
       .btn-success:not(:disabled):not(.disabled).active:focus,
       .btn-success:not(:disabled):not(.disabled):active:focus,
       .show>.btn-success.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(40, 167, 69, .5)
       }
       
       .btn-info {
           color: #fff;
           background-color: #17a2b8;
           border-color: #17a2b8
       }
       
       .btn-info:hover {
           color: #fff;
           background-color: #138496;
           border-color: #117a8b
       }
       
       .btn-info.focus,
       .btn-info:focus {
           box-shadow: 0 0 0 .2rem rgba(23, 162, 184, .5)
       }
       
       .btn-info.disabled,
       .btn-info:disabled {
           color: #fff;
           background-color: #17a2b8;
           border-color: #17a2b8
       }
       
       .btn-info:not(:disabled):not(.disabled).active,
       .btn-info:not(:disabled):not(.disabled):active,
       .show>.btn-info.dropdown-toggle {
           color: #fff;
           background-color: #117a8b;
           border-color: #10707f
       }
       
       .btn-info:not(:disabled):not(.disabled).active:focus,
       .btn-info:not(:disabled):not(.disabled):active:focus,
       .show>.btn-info.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(23, 162, 184, .5)
       }
       
       .btn-warning {
           color: #212529;
           background-color: #ffc107;
           border-color: #ffc107
       }
       
       .btn-warning:hover {
           color: #212529;
           background-color: #e0a800;
           border-color: #d39e00
       }
       
       .btn-warning.focus,
       .btn-warning:focus {
           box-shadow: 0 0 0 .2rem rgba(255, 193, 7, .5)
       }
       
       .btn-warning.disabled,
       .btn-warning:disabled {
           color: #212529;
           background-color: #ffc107;
           border-color: #ffc107
       }
       
       .btn-warning:not(:disabled):not(.disabled).active,
       .btn-warning:not(:disabled):not(.disabled):active,
       .show>.btn-warning.dropdown-toggle {
           color: #212529;
           background-color: #d39e00;
           border-color: #c69500
       }
       
       .btn-warning:not(:disabled):not(.disabled).active:focus,
       .btn-warning:not(:disabled):not(.disabled):active:focus,
       .show>.btn-warning.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(255, 193, 7, .5)
       }
       
       .btn-danger {
           color: #fff;
           background-color: #dc3545;
           border-color: #dc3545
       }
       
       .btn-danger:hover {
           color: #fff;
           background-color: #c82333;
           border-color: #bd2130
       }
       
       .btn-danger.focus,
       .btn-danger:focus {
           box-shadow: 0 0 0 .2rem rgba(220, 53, 69, .5)
       }
       
       .btn-danger.disabled,
       .btn-danger:disabled {
           color: #fff;
           background-color: #dc3545;
           border-color: #dc3545
       }
       
       .btn-danger:not(:disabled):not(.disabled).active,
       .btn-danger:not(:disabled):not(.disabled):active,
       .show>.btn-danger.dropdown-toggle {
           color: #fff;
           background-color: #bd2130;
           border-color: #b21f2d
       }
       
       .btn-danger:not(:disabled):not(.disabled).active:focus,
       .btn-danger:not(:disabled):not(.disabled):active:focus,
       .show>.btn-danger.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(220, 53, 69, .5)
       }
       
       .btn-light {
           color: #212529;
           background-color: #f8f9fa;
           border-color: #f8f9fa
       }
       
       .btn-light:hover {
           color: #212529;
           background-color: #e2e6ea;
           border-color: #dae0e5
       }
       
       .btn-light.focus,
       .btn-light:focus {
           box-shadow: 0 0 0 .2rem rgba(248, 249, 250, .5)
       }
       
       .btn-light.disabled,
       .btn-light:disabled {
           color: #212529;
           background-color: #f8f9fa;
           border-color: #f8f9fa
       }
       
       .btn-light:not(:disabled):not(.disabled).active,
       .btn-light:not(:disabled):not(.disabled):active,
       .show>.btn-light.dropdown-toggle {
           color: #212529;
           background-color: #dae0e5;
           border-color: #d3d9df
       }
       
       .btn-light:not(:disabled):not(.disabled).active:focus,
       .btn-light:not(:disabled):not(.disabled):active:focus,
       .show>.btn-light.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(248, 249, 250, .5)
       }
       
       .btn-dark {
           color: #fff;
           background-color: #343a40;
           border-color: #343a40
       }
       
       .btn-dark:hover {
           color: #fff;
           background-color: #23272b;
           border-color: #1d2124
       }
       
       .btn-dark.focus,
       .btn-dark:focus {
           box-shadow: 0 0 0 .2rem rgba(52, 58, 64, .5)
       }
       
       .btn-dark.disabled,
       .btn-dark:disabled {
           color: #fff;
           background-color: #343a40;
           border-color: #343a40
       }
       
       .btn-dark:not(:disabled):not(.disabled).active,
       .btn-dark:not(:disabled):not(.disabled):active,
       .show>.btn-dark.dropdown-toggle {
           color: #fff;
           background-color: #1d2124;
           border-color: #171a1d
       }
       
       .btn-dark:not(:disabled):not(.disabled).active:focus,
       .btn-dark:not(:disabled):not(.disabled):active:focus,
       .show>.btn-dark.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(52, 58, 64, .5)
       }
       
       .btn-outline-primary {
           color: #007bff;
           background-color: transparent;
           background-image: none;
           border-color: #007bff
       }
       
       .btn-outline-primary:hover {
           color: #fff;
           background-color: #007bff;
           border-color: #007bff
       }
       
       .btn-outline-primary.focus,
       .btn-outline-primary:focus {
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .5)
       }
       
       .btn-outline-primary.disabled,
       .btn-outline-primary:disabled {
           color: #007bff;
           background-color: transparent
       }
       
       .btn-outline-primary:not(:disabled):not(.disabled).active,
       .btn-outline-primary:not(:disabled):not(.disabled):active,
       .show>.btn-outline-primary.dropdown-toggle {
           color: #fff;
           background-color: #007bff;
           border-color: #007bff
       }
       
       .btn-outline-primary:not(:disabled):not(.disabled).active:focus,
       .btn-outline-primary:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-primary.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .5)
       }
       
       .btn-outline-secondary {
           color: #6c757d;
           background-color: transparent;
           background-image: none;
           border-color: #6c757d
       }
       
       .btn-outline-secondary:hover {
           color: #fff;
           background-color: #6c757d;
           border-color: #6c757d
       }
       
       .btn-outline-secondary.focus,
       .btn-outline-secondary:focus {
           box-shadow: 0 0 0 .2rem rgba(108, 117, 125, .5)
       }
       
       .btn-outline-secondary.disabled,
       .btn-outline-secondary:disabled {
           color: #6c757d;
           background-color: transparent
       }
       
       .btn-outline-secondary:not(:disabled):not(.disabled).active,
       .btn-outline-secondary:not(:disabled):not(.disabled):active,
       .show>.btn-outline-secondary.dropdown-toggle {
           color: #fff;
           background-color: #6c757d;
           border-color: #6c757d
       }
       
       .btn-outline-secondary:not(:disabled):not(.disabled).active:focus,
       .btn-outline-secondary:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-secondary.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(108, 117, 125, .5)
       }
       
       .btn-outline-success {
           color: #28a745;
           background-color: transparent;
           background-image: none;
           border-color: #28a745
       }
       
       .btn-outline-success:hover {
           color: #fff;
           background-color: #28a745;
           border-color: #28a745
       }
       
       .btn-outline-success.focus,
       .btn-outline-success:focus {
           box-shadow: 0 0 0 .2rem rgba(40, 167, 69, .5)
       }
       
       .btn-outline-success.disabled,
       .btn-outline-success:disabled {
           color: #28a745;
           background-color: transparent
       }
       
       .btn-outline-success:not(:disabled):not(.disabled).active,
       .btn-outline-success:not(:disabled):not(.disabled):active,
       .show>.btn-outline-success.dropdown-toggle {
           color: #fff;
           background-color: #28a745;
           border-color: #28a745
       }
       
       .btn-outline-success:not(:disabled):not(.disabled).active:focus,
       .btn-outline-success:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-success.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(40, 167, 69, .5)
       }
       
       .btn-outline-info {
           color: #17a2b8;
           background-color: transparent;
           background-image: none;
           border-color: #17a2b8
       }
       
       .btn-outline-info:hover {
           color: #fff;
           background-color: #17a2b8;
           border-color: #17a2b8
       }
       
       .btn-outline-info.focus,
       .btn-outline-info:focus {
           box-shadow: 0 0 0 .2rem rgba(23, 162, 184, .5)
       }
       
       .btn-outline-info.disabled,
       .btn-outline-info:disabled {
           color: #17a2b8;
           background-color: transparent
       }
       
       .btn-outline-info:not(:disabled):not(.disabled).active,
       .btn-outline-info:not(:disabled):not(.disabled):active,
       .show>.btn-outline-info.dropdown-toggle {
           color: #fff;
           background-color: #17a2b8;
           border-color: #17a2b8
       }
       
       .btn-outline-info:not(:disabled):not(.disabled).active:focus,
       .btn-outline-info:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-info.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(23, 162, 184, .5)
       }
       
       .btn-outline-warning {
           color: #ffc107;
           background-color: transparent;
           background-image: none;
           border-color: #ffc107
       }
       
       .btn-outline-warning:hover {
           color: #212529;
           background-color: #ffc107;
           border-color: #ffc107
       }
       
       .btn-outline-warning.focus,
       .btn-outline-warning:focus {
           box-shadow: 0 0 0 .2rem rgba(255, 193, 7, .5)
       }
       
       .btn-outline-warning.disabled,
       .btn-outline-warning:disabled {
           color: #ffc107;
           background-color: transparent
       }
       
       .btn-outline-warning:not(:disabled):not(.disabled).active,
       .btn-outline-warning:not(:disabled):not(.disabled):active,
       .show>.btn-outline-warning.dropdown-toggle {
           color: #212529;
           background-color: #ffc107;
           border-color: #ffc107
       }
       
       .btn-outline-warning:not(:disabled):not(.disabled).active:focus,
       .btn-outline-warning:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-warning.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(255, 193, 7, .5)
       }
       
       .btn-outline-danger {
           color: #dc3545;
           background-color: transparent;
           background-image: none;
           border-color: #dc3545
       }
       
       .btn-outline-danger:hover {
           color: #fff;
           background-color: #dc3545;
           border-color: #dc3545
       }
       
       .btn-outline-danger.focus,
       .btn-outline-danger:focus {
           box-shadow: 0 0 0 .2rem rgba(220, 53, 69, .5)
       }
       
       .btn-outline-danger.disabled,
       .btn-outline-danger:disabled {
           color: #dc3545;
           background-color: transparent
       }
       
       .btn-outline-danger:not(:disabled):not(.disabled).active,
       .btn-outline-danger:not(:disabled):not(.disabled):active,
       .show>.btn-outline-danger.dropdown-toggle {
           color: #fff;
           background-color: #dc3545;
           border-color: #dc3545
       }
       
       .btn-outline-danger:not(:disabled):not(.disabled).active:focus,
       .btn-outline-danger:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-danger.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(220, 53, 69, .5)
       }
       
       .btn-outline-light {
           color: #f8f9fa;
           background-color: transparent;
           background-image: none;
           border-color: #f8f9fa
       }
       
       .btn-outline-light:hover {
           color: #212529;
           background-color: #f8f9fa;
           border-color: #f8f9fa
       }
       
       .btn-outline-light.focus,
       .btn-outline-light:focus {
           box-shadow: 0 0 0 .2rem rgba(248, 249, 250, .5)
       }
       
       .btn-outline-light.disabled,
       .btn-outline-light:disabled {
           color: #f8f9fa;
           background-color: transparent
       }
       
       .btn-outline-light:not(:disabled):not(.disabled).active,
       .btn-outline-light:not(:disabled):not(.disabled):active,
       .show>.btn-outline-light.dropdown-toggle {
           color: #212529;
           background-color: #f8f9fa;
           border-color: #f8f9fa
       }
       
       .btn-outline-light:not(:disabled):not(.disabled).active:focus,
       .btn-outline-light:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-light.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(248, 249, 250, .5)
       }
       
       .btn-outline-dark {
           color: #343a40;
           background-color: transparent;
           background-image: none;
           border-color: #343a40
       }
       
       .btn-outline-dark:hover {
           color: #fff;
           background-color: #343a40;
           border-color: #343a40
       }
       
       .btn-outline-dark.focus,
       .btn-outline-dark:focus {
           box-shadow: 0 0 0 .2rem rgba(52, 58, 64, .5)
       }
       
       .btn-outline-dark.disabled,
       .btn-outline-dark:disabled {
           color: #343a40;
           background-color: transparent
       }
       
       .btn-outline-dark:not(:disabled):not(.disabled).active,
       .btn-outline-dark:not(:disabled):not(.disabled):active,
       .show>.btn-outline-dark.dropdown-toggle {
           color: #fff;
           background-color: #343a40;
           border-color: #343a40
       }
       
       .btn-outline-dark:not(:disabled):not(.disabled).active:focus,
       .btn-outline-dark:not(:disabled):not(.disabled):active:focus,
       .show>.btn-outline-dark.dropdown-toggle:focus {
           box-shadow: 0 0 0 .2rem rgba(52, 58, 64, .5)
       }
       
       .btn-link {
           font-weight: 400;
           color: #007bff;
           background-color: transparent
       }
       
       .btn-link:hover {
           color: #0056b3;
           text-decoration: underline;
           background-color: transparent;
           border-color: transparent
       }
       
       .btn-link.focus,
       .btn-link:focus {
           text-decoration: underline;
           border-color: transparent;
           box-shadow: none
       }
       
       .btn-link.disabled,
       .btn-link:disabled {
           color: #6c757d
       }
       
       .btn-group-lg>.btn,
       .btn-lg {
           padding: .5rem 1rem;
           font-size: 1.25rem;
           line-height: 1.5;
           border-radius: .3rem
       }
       
       .btn-group-sm>.btn,
       .btn-sm {
           padding: .25rem .5rem;
           font-size: .875rem;
           line-height: 1.5;
           border-radius: .2rem
       }
       
       .btn-block {
           display: block;
           width: 100%
       }
       
       .btn-block+.btn-block {
           margin-top: .5rem
       }
       
       input[type=button].btn-block,
       input[type=reset].btn-block,
       input[type=submit].btn-block {
           width: 100%
       }
       
       .fade {
           opacity: 0;
           transition: opacity .15s linear
       }
       
       .fade.show {
           opacity: 1
       }
       
       .collapse {
           display: none
       }
       
       .collapse.show {
           display: block
       }
       
       tr.collapse.show {
           display: table-row
       }
       
       tbody.collapse.show {
           display: table-row-group
       }
       
       .collapsing {
           position: relative;
           height: 0;
           overflow: hidden;
           transition: height .35s ease
       }
       
       .dropdown,
       .dropup {
           position: relative
       }
       
       .dropdown-toggle::after {
           display: inline-block;
           width: 0;
           height: 0;
           margin-left: .255em;
           vertical-align: .255em;
           content: "";
           border-top: .3em solid;
           border-right: .3em solid transparent;
           border-bottom: 0;
           border-left: .3em solid transparent
       }
       
       .dropdown-toggle:empty::after {
           margin-left: 0
       }
       
       .dropdown-menu {
           position: absolute;
           top: 100%;
           left: 0;
           z-index: 1000;
           display: none;
           float: left;
           min-width: 10rem;
           padding: .5rem 0;
           margin: .125rem 0 0;
           font-size: 1rem;
           color: #212529;
           text-align: left;
           list-style: none;
           background-color: #fff;
           background-clip: padding-box;
           border: 1px solid rgba(0, 0, 0, .15);
           border-radius: .25rem
       }
       
       .dropup .dropdown-menu {
           margin-top: 0;
           margin-bottom: .125rem
       }
       
       .dropup .dropdown-toggle::after {
           display: inline-block;
           width: 0;
           height: 0;
           margin-left: .255em;
           vertical-align: .255em;
           content: "";
           border-top: 0;
           border-right: .3em solid transparent;
           border-bottom: .3em solid;
           border-left: .3em solid transparent
       }
       
       .dropup .dropdown-toggle:empty::after {
           margin-left: 0
       }
       
       .dropright .dropdown-menu {
           margin-top: 0;
           margin-left: .125rem
       }
       
       .dropright .dropdown-toggle::after {
           display: inline-block;
           width: 0;
           height: 0;
           margin-left: .255em;
           vertical-align: .255em;
           content: "";
           border-top: .3em solid transparent;
           border-bottom: .3em solid transparent;
           border-left: .3em solid
       }
       
       .dropright .dropdown-toggle:empty::after {
           margin-left: 0
       }
       
       .dropright .dropdown-toggle::after {
           vertical-align: 0
       }
       
       .dropleft .dropdown-menu {
           margin-top: 0;
           margin-right: .125rem
       }
       
       .dropleft .dropdown-toggle::after {
           display: inline-block;
           width: 0;
           height: 0;
           margin-left: .255em;
           vertical-align: .255em;
           content: ""
       }
       
       .dropleft .dropdown-toggle::after {
           display: none
       }
       
       .dropleft .dropdown-toggle::before {
           display: inline-block;
           width: 0;
           height: 0;
           margin-right: .255em;
           vertical-align: .255em;
           content: "";
           border-top: .3em solid transparent;
           border-right: .3em solid;
           border-bottom: .3em solid transparent
       }
       
       .dropleft .dropdown-toggle:empty::after {
           margin-left: 0
       }
       
       .dropleft .dropdown-toggle::before {
           vertical-align: 0
       }
       
       .dropdown-divider {
           height: 0;
           margin: .5rem 0;
           overflow: hidden;
           border-top: 1px solid #e9ecef
       }
       
       .dropdown-item {
           display: block;
           width: 100%;
           padding: .25rem 1.5rem;
           clear: both;
           font-weight: 400;
           color: #212529;
           text-align: inherit;
           white-space: nowrap;
           background-color: transparent;
           border: 0
       }
       
       .dropdown-item:focus,
       .dropdown-item:hover {
           color: #16181b;
           text-decoration: none;
           background-color: #f8f9fa
       }
       
       .dropdown-item.active,
       .dropdown-item:active {
           color: #fff;
           text-decoration: none;
           background-color: #007bff
       }
       
       .dropdown-item.disabled,
       .dropdown-item:disabled {
           color: #6c757d;
           background-color: transparent
       }
       
       .dropdown-menu.show {
           display: block
       }
       
       .dropdown-header {
           display: block;
           padding: .5rem 1.5rem;
           margin-bottom: 0;
           font-size: .875rem;
           color: #6c757d;
           white-space: nowrap
       }
       
       .btn-group,
       .btn-group-vertical {
           position: relative;
           display: -webkit-inline-box;
           display: -ms-inline-flexbox;
           display: inline-flex;
           vertical-align: middle
       }
       
       .btn-group-vertical>.btn,
       .btn-group>.btn {
           position: relative;
           -webkit-box-flex: 0;
           -ms-flex: 0 1 auto;
           flex: 0 1 auto
       }
       
       .btn-group-vertical>.btn:hover,
       .btn-group>.btn:hover {
           z-index: 1
       }
       
       .btn-group-vertical>.btn.active,
       .btn-group-vertical>.btn:active,
       .btn-group-vertical>.btn:focus,
       .btn-group>.btn.active,
       .btn-group>.btn:active,
       .btn-group>.btn:focus {
           z-index: 1
       }
       
       .btn-group .btn+.btn,
       .btn-group .btn+.btn-group,
       .btn-group .btn-group+.btn,
       .btn-group .btn-group+.btn-group,
       .btn-group-vertical .btn+.btn,
       .btn-group-vertical .btn+.btn-group,
       .btn-group-vertical .btn-group+.btn,
       .btn-group-vertical .btn-group+.btn-group {
           margin-left: -1px
       }
       
       .btn-toolbar {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           -webkit-box-pack: start;
           -ms-flex-pack: start;
           justify-content: flex-start
       }
       
       .btn-toolbar .input-group {
           width: auto
       }
       
       .btn-group>.btn:first-child {
           margin-left: 0
       }
       
       .btn-group>.btn-group:not(:last-child)>.btn,
       .btn-group>.btn:not(:last-child):not(.dropdown-toggle) {
           border-top-right-radius: 0;
           border-bottom-right-radius: 0
       }
       
       .btn-group>.btn-group:not(:first-child)>.btn,
       .btn-group>.btn:not(:first-child) {
           border-top-left-radius: 0;
           border-bottom-left-radius: 0
       }
       
       .dropdown-toggle-split {
           padding-right: .5625rem;
           padding-left: .5625rem
       }
       
       .dropdown-toggle-split::after {
           margin-left: 0
       }
       
       .btn-group-sm>.btn+.dropdown-toggle-split,
       .btn-sm+.dropdown-toggle-split {
           padding-right: .375rem;
           padding-left: .375rem
       }
       
       .btn-group-lg>.btn+.dropdown-toggle-split,
       .btn-lg+.dropdown-toggle-split {
           padding-right: .75rem;
           padding-left: .75rem
       }
       
       .btn-group-vertical {
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column;
           -webkit-box-align: start;
           -ms-flex-align: start;
           align-items: flex-start;
           -webkit-box-pack: center;
           -ms-flex-pack: center;
           justify-content: center
       }
       
       .btn-group-vertical .btn,
       .btn-group-vertical .btn-group {
           width: 100%
       }
       
       .btn-group-vertical>.btn+.btn,
       .btn-group-vertical>.btn+.btn-group,
       .btn-group-vertical>.btn-group+.btn,
       .btn-group-vertical>.btn-group+.btn-group {
           margin-top: -1px;
           margin-left: 0
       }
       
       .btn-group-vertical>.btn-group:not(:last-child)>.btn,
       .btn-group-vertical>.btn:not(:last-child):not(.dropdown-toggle) {
           border-bottom-right-radius: 0;
           border-bottom-left-radius: 0
       }
       
       .btn-group-vertical>.btn-group:not(:first-child)>.btn,
       .btn-group-vertical>.btn:not(:first-child) {
           border-top-left-radius: 0;
           border-top-right-radius: 0
       }
       
       .btn-group-toggle>.btn,
       .btn-group-toggle>.btn-group>.btn {
           margin-bottom: 0
       }
       
       .btn-group-toggle>.btn input[type=checkbox],
       .btn-group-toggle>.btn input[type=radio],
       .btn-group-toggle>.btn-group>.btn input[type=checkbox],
       .btn-group-toggle>.btn-group>.btn input[type=radio] {
           position: absolute;
           clip: rect(0, 0, 0, 0);
           pointer-events: none
       }
       
       .input-group {
           position: relative;
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           -webkit-box-align: stretch;
           -ms-flex-align: stretch;
           align-items: stretch;
           width: 100%
       }
       
       .input-group>.custom-file,
       .input-group>.custom-select,
       .input-group>.form-control {
           position: relative;
           -webkit-box-flex: 1;
           -ms-flex: 1 1 auto;
           flex: 1 1 auto;
           width: 1%;
           margin-bottom: 0
       }
       
       .input-group>.custom-file:focus,
       .input-group>.custom-select:focus,
       .input-group>.form-control:focus {
           z-index: 3
       }
       
       .input-group>.custom-file+.custom-file,
       .input-group>.custom-file+.custom-select,
       .input-group>.custom-file+.form-control,
       .input-group>.custom-select+.custom-file,
       .input-group>.custom-select+.custom-select,
       .input-group>.custom-select+.form-control,
       .input-group>.form-control+.custom-file,
       .input-group>.form-control+.custom-select,
       .input-group>.form-control+.form-control {
           margin-left: -1px
       }
       
       .input-group>.custom-select:not(:last-child),
       .input-group>.form-control:not(:last-child) {
           border-top-right-radius: 0;
           border-bottom-right-radius: 0
       }
       
       .input-group>.custom-select:not(:first-child),
       .input-group>.form-control:not(:first-child) {
           border-top-left-radius: 0;
           border-bottom-left-radius: 0
       }
       
       .input-group>.custom-file {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center
       }
       
       .input-group>.custom-file:not(:last-child) .custom-file-label,
       .input-group>.custom-file:not(:last-child) .custom-file-label::before {
           border-top-right-radius: 0;
           border-bottom-right-radius: 0
       }
       
       .input-group>.custom-file:not(:first-child) .custom-file-label,
       .input-group>.custom-file:not(:first-child) .custom-file-label::before {
           border-top-left-radius: 0;
           border-bottom-left-radius: 0
       }
       
       .input-group-append,
       .input-group-prepend {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex
       }
       
       .input-group-append .btn,
       .input-group-prepend .btn {
           position: relative;
           z-index: 2
       }
       
       .input-group-append .btn+.btn,
       .input-group-append .btn+.input-group-text,
       .input-group-append .input-group-text+.btn,
       .input-group-append .input-group-text+.input-group-text,
       .input-group-prepend .btn+.btn,
       .input-group-prepend .btn+.input-group-text,
       .input-group-prepend .input-group-text+.btn,
       .input-group-prepend .input-group-text+.input-group-text {
           margin-left: -1px
       }
       
       .input-group-prepend {
           margin-right: -1px
       }
       
       .input-group-append {
           margin-left: -1px
       }
       
       .input-group-text {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           padding: .375rem .75rem;
           margin-bottom: 0;
           font-size: 1rem;
           font-weight: 400;
           line-height: 1.5;
           color: #495057;
           text-align: center;
           white-space: nowrap;
           background-color: #e9ecef;
           border: 1px solid #ced4da;
           border-radius: .25rem
       }
       
       .input-group-text input[type=checkbox],
       .input-group-text input[type=radio] {
           margin-top: 0
       }
       
       .input-group>.input-group-append:last-child>.btn:not(:last-child):not(.dropdown-toggle),
       .input-group>.input-group-append:last-child>.input-group-text:not(:last-child),
       .input-group>.input-group-append:not(:last-child)>.btn,
       .input-group>.input-group-append:not(:last-child)>.input-group-text,
       .input-group>.input-group-prepend>.btn,
       .input-group>.input-group-prepend>.input-group-text {
           border-top-right-radius: 0;
           border-bottom-right-radius: 0
       }
       
       .input-group>.input-group-append>.btn,
       .input-group>.input-group-append>.input-group-text,
       .input-group>.input-group-prepend:first-child>.btn:not(:first-child),
       .input-group>.input-group-prepend:first-child>.input-group-text:not(:first-child),
       .input-group>.input-group-prepend:not(:first-child)>.btn,
       .input-group>.input-group-prepend:not(:first-child)>.input-group-text {
           border-top-left-radius: 0;
           border-bottom-left-radius: 0
       }
       
       .custom-control {
           position: relative;
           display: block;
           min-height: 1.5rem;
           padding-left: 1.5rem
       }
       
       .custom-control-inline {
           display: -webkit-inline-box;
           display: -ms-inline-flexbox;
           display: inline-flex;
           margin-right: 1rem
       }
       
       .custom-control-input {
           position: absolute;
           z-index: -1;
           opacity: 0
       }
       
       .custom-control-input:checked~.custom-control-label::before {
           color: #fff;
           background-color: #007bff
       }
       
       .custom-control-input:focus~.custom-control-label::before {
           box-shadow: 0 0 0 1px #fff, 0 0 0 .2rem rgba(0, 123, 255, .25)
       }
       
       .custom-control-input:active~.custom-control-label::before {
           color: #fff;
           background-color: #b3d7ff
       }
       
       .custom-control-input:disabled~.custom-control-label {
           color: #6c757d
       }
       
       .custom-control-input:disabled~.custom-control-label::before {
           background-color: #e9ecef
       }
       
       .custom-control-label {
           margin-bottom: 0
       }
       
       .custom-control-label::before {
           position: absolute;
           top: .25rem;
           left: 0;
           display: block;
           width: 1rem;
           height: 1rem;
           pointer-events: none;
           content: "";
           -webkit-user-select: none;
           -moz-user-select: none;
           -ms-user-select: none;
           user-select: none;
           background-color: #dee2e6
       }
       
       .custom-control-label::after {
           position: absolute;
           top: .25rem;
           left: 0;
           display: block;
           width: 1rem;
           height: 1rem;
           content: "";
           background-repeat: no-repeat;
           background-position: center center;
           background-size: 50% 50%
       }
       
       .custom-checkbox .custom-control-label::before {
           border-radius: .25rem
       }
       
       .custom-checkbox .custom-control-input:checked~.custom-control-label::before {
           background-color: #007bff
       }
       
       .custom-checkbox .custom-control-input:checked~.custom-control-label::after {
           background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3E%3Cpath fill='%23fff' d='M6.564.75l-3.59 3.612-1.538-1.55L0 4.26 2.974 7.25 8 2.193z'/%3E%3C/svg%3E")
       }
       
       .custom-checkbox .custom-control-input:indeterminate~.custom-control-label::before {
           background-color: #007bff
       }
       
       .custom-checkbox .custom-control-input:indeterminate~.custom-control-label::after {
           background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 4'%3E%3Cpath stroke='%23fff' d='M0 2h4'/%3E%3C/svg%3E")
       }
       
       .custom-checkbox .custom-control-input:disabled:checked~.custom-control-label::before {
           background-color: rgba(0, 123, 255, .5)
       }
       
       .custom-checkbox .custom-control-input:disabled:indeterminate~.custom-control-label::before {
           background-color: rgba(0, 123, 255, .5)
       }
       
       .custom-radio .custom-control-label::before {
           border-radius: 50%
       }
       
       .custom-radio .custom-control-input:checked~.custom-control-label::before {
           background-color: #007bff
       }
       
       .custom-radio .custom-control-input:checked~.custom-control-label::after {
           background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3E%3Ccircle r='3' fill='%23fff'/%3E%3C/svg%3E")
       }
       
       .custom-radio .custom-control-input:disabled:checked~.custom-control-label::before {
           background-color: rgba(0, 123, 255, .5)
       }
       
       .custom-select {
           display: inline-block;
           width: 100%;
           height: calc(2.25rem + 2px);
           padding: .375rem 1.75rem .375rem .75rem;
           line-height: 1.5;
           color: #495057;
           vertical-align: middle;
           background: #fff url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3E%3Cpath fill='%23343a40' d='M2 0L0 2h4zm0 5L0 3h4z'/%3E%3C/svg%3E") no-repeat right .75rem center;
           background-size: 8px 10px;
           border: 1px solid #ced4da;
           border-radius: .25rem;
           -webkit-appearance: none;
           -moz-appearance: none;
           appearance: none
       }
       
       .custom-select:focus {
           border-color: #80bdff;
           outline: 0;
           box-shadow: inset 0 1px 2px rgba(0, 0, 0, .075), 0 0 5px rgba(128, 189, 255, .5)
       }
       
       .custom-select:focus::-ms-value {
           color: #495057;
           background-color: #fff
       }
       
       .custom-select[multiple],
       .custom-select[size]:not([size="1"]) {
           height: auto;
           padding-right: .75rem;
           background-image: none
       }
       
       .custom-select:disabled {
           color: #6c757d;
           background-color: #e9ecef
       }
       
       .custom-select::-ms-expand {
           opacity: 0
       }
       
       .custom-select-sm {
           height: calc(1.8125rem + 2px);
           padding-top: .375rem;
           padding-bottom: .375rem;
           font-size: 75%
       }
       
       .custom-select-lg {
           height: calc(2.875rem + 2px);
           padding-top: .375rem;
           padding-bottom: .375rem;
           font-size: 125%
       }
       
       .custom-file {
           position: relative;
           display: inline-block;
           width: 100%;
           height: calc(2.25rem + 2px);
           margin-bottom: 0
       }
       
       .custom-file-input {
           position: relative;
           z-index: 2;
           width: 100%;
           height: calc(2.25rem + 2px);
           margin: 0;
           opacity: 0
       }
       
       .custom-file-input:focus~.custom-file-control {
           border-color: #80bdff;
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .25)
       }
       
       .custom-file-input:focus~.custom-file-control::before {
           border-color: #80bdff
       }
       
       .custom-file-input:lang(en)~.custom-file-label::after {
           content: "Browse"
       }
       
       .custom-file-label {
           position: absolute;
           top: 0;
           right: 0;
           left: 0;
           z-index: 1;
           height: calc(2.25rem + 2px);
           padding: .375rem .75rem;
           line-height: 1.5;
           color: #495057;
           background-color: #fff;
           border: 1px solid #ced4da;
           border-radius: .25rem
       }
       
       .custom-file-label::after {
           position: absolute;
           top: 0;
           right: 0;
           bottom: 0;
           z-index: 3;
           display: block;
           height: calc(calc(2.25rem + 2px) - 1px * 2);
           padding: .375rem .75rem;
           line-height: 1.5;
           color: #495057;
           content: "Browse";
           background-color: #e9ecef;
           border-left: 1px solid #ced4da;
           border-radius: 0 .25rem .25rem 0
       }
       
       .nav {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           padding-left: 0;
           margin-bottom: 0;
           list-style: none
       }
       
       .nav-link {
           display: block;
           padding: .5rem 1rem
       }
       
       .nav-link:focus,
       .nav-link:hover {
           text-decoration: none
       }
       
       .nav-link.disabled {
           color: #6c757d
       }
       
       .nav-tabs {
           border-bottom: 1px solid #dee2e6
       }
       
       .nav-tabs .nav-item {
           margin-bottom: -1px
       }
       
       .nav-tabs .nav-link {
           border: 1px solid transparent;
           border-top-left-radius: .25rem;
           border-top-right-radius: .25rem
       }
       
       .nav-tabs .nav-link:focus,
       .nav-tabs .nav-link:hover {
           border-color: #e9ecef #e9ecef #dee2e6
       }
       
       .nav-tabs .nav-link.disabled {
           color: #6c757d;
           background-color: transparent;
           border-color: transparent
       }
       
       .nav-tabs .nav-item.show .nav-link,
       .nav-tabs .nav-link.active {
           color: #495057;
           background-color: #fff;
           border-color: #dee2e6 #dee2e6 #fff
       }
       
       .nav-tabs .dropdown-menu {
           margin-top: -1px;
           border-top-left-radius: 0;
           border-top-right-radius: 0
       }
       
       .nav-pills .nav-link {
           border-radius: .25rem
       }
       
       .nav-pills .nav-link.active,
       .nav-pills .show>.nav-link {
           color: #fff;
           background-color: #007bff
       }
       
       .nav-fill .nav-item {
           -webkit-box-flex: 1;
           -ms-flex: 1 1 auto;
           flex: 1 1 auto;
           text-align: center
       }
       
       .nav-justified .nav-item {
           -ms-flex-preferred-size: 0;
           flex-basis: 0;
           -webkit-box-flex: 1;
           -ms-flex-positive: 1;
           flex-grow: 1;
           text-align: center
       }
       
       .tab-content>.tab-pane {
           display: none
       }
       
       .tab-content>.active {
           display: block
       }
       
       .navbar {
           position: relative;
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           -webkit-box-pack: justify;
           -ms-flex-pack: justify;
           justify-content: space-between;
           padding: .5rem 1rem
       }
       
       .navbar>.container,
       .navbar>.container-fluid {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           -webkit-box-pack: justify;
           -ms-flex-pack: justify;
           justify-content: space-between
       }
       
       .navbar-brand {
           display: inline-block;
           padding-top: .3125rem;
           padding-bottom: .3125rem;
           margin-right: 1rem;
           font-size: 1.25rem;
           line-height: inherit;
           white-space: nowrap
       }
       
       .navbar-brand:focus,
       .navbar-brand:hover {
           text-decoration: none
       }
       
       .navbar-nav {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column;
           padding-left: 0;
           margin-bottom: 0;
           list-style: none
       }
       
       .navbar-nav .nav-link {
           padding-right: 0;
           padding-left: 0
       }
       
       .navbar-nav .dropdown-menu {
           position: static;
           float: none
       }
       
       .navbar-text {
           display: inline-block;
           padding-top: .5rem;
           padding-bottom: .5rem
       }
       
       .navbar-collapse {
           -ms-flex-preferred-size: 100%;
           flex-basis: 100%;
           -webkit-box-flex: 1;
           -ms-flex-positive: 1;
           flex-grow: 1;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center
       }
       
       .navbar-toggler {
           padding: .25rem .75rem;
           font-size: 1.25rem;
           line-height: 1;
           background-color: transparent;
           border: 1px solid transparent;
           border-radius: .25rem
       }
       
       .navbar-toggler:focus,
       .navbar-toggler:hover {
           text-decoration: none
       }
       
       .navbar-toggler:not(:disabled):not(.disabled) {
           cursor: pointer
       }
       
       .navbar-toggler-icon {
           display: inline-block;
           width: 1.5em;
           height: 1.5em;
           vertical-align: middle;
           content: "";
           background: no-repeat center center;
           background-size: 100% 100%
       }
       
       @media (max-width:575.98px) {
           .navbar-expand-sm>.container,
           .navbar-expand-sm>.container-fluid {
               padding-right: 0;
               padding-left: 0
           }
       }
       
       @media (min-width:576px) {
           .navbar-expand-sm {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-flow: row nowrap;
               flex-flow: row nowrap;
               -webkit-box-pack: start;
               -ms-flex-pack: start;
               justify-content: flex-start
           }
           .navbar-expand-sm .navbar-nav {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-direction: row;
               flex-direction: row
           }
           .navbar-expand-sm .navbar-nav .dropdown-menu {
               position: absolute
           }
           .navbar-expand-sm .navbar-nav .dropdown-menu-right {
               right: 0;
               left: auto
           }
           .navbar-expand-sm .navbar-nav .nav-link {
               padding-right: .5rem;
               padding-left: .5rem
           }
           .navbar-expand-sm>.container,
           .navbar-expand-sm>.container-fluid {
               -ms-flex-wrap: nowrap;
               flex-wrap: nowrap
           }
           .navbar-expand-sm .navbar-collapse {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important;
               -ms-flex-preferred-size: auto;
               flex-basis: auto
           }
           .navbar-expand-sm .navbar-toggler {
               display: none
           }
           .navbar-expand-sm .dropup .dropdown-menu {
               top: auto;
               bottom: 100%
           }
       }
       
       @media (max-width:767.98px) {
           .navbar-expand-md>.container,
           .navbar-expand-md>.container-fluid {
               padding-right: 0;
               padding-left: 0
           }
       }
       
       @media (min-width:768px) {
           .navbar-expand-md {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-flow: row nowrap;
               flex-flow: row nowrap;
               -webkit-box-pack: start;
               -ms-flex-pack: start;
               justify-content: flex-start
           }
           .navbar-expand-md .navbar-nav {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-direction: row;
               flex-direction: row
           }
           .navbar-expand-md .navbar-nav .dropdown-menu {
               position: absolute
           }
           .navbar-expand-md .navbar-nav .dropdown-menu-right {
               right: 0;
               left: auto
           }
           .navbar-expand-md .navbar-nav .nav-link {
               padding-right: .5rem;
               padding-left: .5rem
           }
           .navbar-expand-md>.container,
           .navbar-expand-md>.container-fluid {
               -ms-flex-wrap: nowrap;
               flex-wrap: nowrap
           }
           .navbar-expand-md .navbar-collapse {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important;
               -ms-flex-preferred-size: auto;
               flex-basis: auto
           }
           .navbar-expand-md .navbar-toggler {
               display: none
           }
           .navbar-expand-md .dropup .dropdown-menu {
               top: auto;
               bottom: 100%
           }
       }
       
       @media (max-width:991.98px) {
           .navbar-expand-lg>.container,
           .navbar-expand-lg>.container-fluid {
               padding-right: 0;
               padding-left: 0
           }
       }
       
       @media (min-width:992px) {
           .navbar-expand-lg {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-flow: row nowrap;
               flex-flow: row nowrap;
               -webkit-box-pack: start;
               -ms-flex-pack: start;
               justify-content: flex-start
           }
           .navbar-expand-lg .navbar-nav {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-direction: row;
               flex-direction: row
           }
           .navbar-expand-lg .navbar-nav .dropdown-menu {
               position: absolute
           }
           .navbar-expand-lg .navbar-nav .dropdown-menu-right {
               right: 0;
               left: auto
           }
           .navbar-expand-lg .navbar-nav .nav-link {
               padding-right: .5rem;
               padding-left: .5rem
           }
           .navbar-expand-lg>.container,
           .navbar-expand-lg>.container-fluid {
               -ms-flex-wrap: nowrap;
               flex-wrap: nowrap
           }
           .navbar-expand-lg .navbar-collapse {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important;
               -ms-flex-preferred-size: auto;
               flex-basis: auto
           }
           .navbar-expand-lg .navbar-toggler {
               display: none
           }
           .navbar-expand-lg .dropup .dropdown-menu {
               top: auto;
               bottom: 100%
           }
       }
       
       @media (max-width:1199.98px) {
           .navbar-expand-xl>.container,
           .navbar-expand-xl>.container-fluid {
               padding-right: 0;
               padding-left: 0
           }
       }
       
       @media (min-width:1200px) {
           .navbar-expand-xl {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-flow: row nowrap;
               flex-flow: row nowrap;
               -webkit-box-pack: start;
               -ms-flex-pack: start;
               justify-content: flex-start
           }
           .navbar-expand-xl .navbar-nav {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-direction: row;
               flex-direction: row
           }
           .navbar-expand-xl .navbar-nav .dropdown-menu {
               position: absolute
           }
           .navbar-expand-xl .navbar-nav .dropdown-menu-right {
               right: 0;
               left: auto
           }
           .navbar-expand-xl .navbar-nav .nav-link {
               padding-right: .5rem;
               padding-left: .5rem
           }
           .navbar-expand-xl>.container,
           .navbar-expand-xl>.container-fluid {
               -ms-flex-wrap: nowrap;
               flex-wrap: nowrap
           }
           .navbar-expand-xl .navbar-collapse {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important;
               -ms-flex-preferred-size: auto;
               flex-basis: auto
           }
           .navbar-expand-xl .navbar-toggler {
               display: none
           }
           .navbar-expand-xl .dropup .dropdown-menu {
               top: auto;
               bottom: 100%
           }
       }
       
       .navbar-expand {
           -webkit-box-orient: horizontal;
           -webkit-box-direction: normal;
           -ms-flex-flow: row nowrap;
           flex-flow: row nowrap;
           -webkit-box-pack: start;
           -ms-flex-pack: start;
           justify-content: flex-start
       }
       
       .navbar-expand>.container,
       .navbar-expand>.container-fluid {
           padding-right: 0;
           padding-left: 0
       }
       
       .navbar-expand .navbar-nav {
           -webkit-box-orient: horizontal;
           -webkit-box-direction: normal;
           -ms-flex-direction: row;
           flex-direction: row
       }
       
       .navbar-expand .navbar-nav .dropdown-menu {
           position: absolute
       }
       
       .navbar-expand .navbar-nav .dropdown-menu-right {
           right: 0;
           left: auto
       }
       
       .navbar-expand .navbar-nav .nav-link {
           padding-right: .5rem;
           padding-left: .5rem
       }
       
       .navbar-expand>.container,
       .navbar-expand>.container-fluid {
           -ms-flex-wrap: nowrap;
           flex-wrap: nowrap
       }
       
       .navbar-expand .navbar-collapse {
           display: -webkit-box!important;
           display: -ms-flexbox!important;
           display: flex!important;
           -ms-flex-preferred-size: auto;
           flex-basis: auto
       }
       
       .navbar-expand .navbar-toggler {
           display: none
       }
       
       .navbar-expand .dropup .dropdown-menu {
           top: auto;
           bottom: 100%
       }
       
       .navbar-light .navbar-brand {
           color: rgba(0, 0, 0, .9)
       }
       
       .navbar-light .navbar-brand:focus,
       .navbar-light .navbar-brand:hover {
           color: rgba(0, 0, 0, .9)
       }
       
       .navbar-light .navbar-nav .nav-link {
           color: rgba(0, 0, 0, .5)
       }
       
       .navbar-light .navbar-nav .nav-link:focus,
       .navbar-light .navbar-nav .nav-link:hover {
           color: rgba(0, 0, 0, .7)
       }
       
       .navbar-light .navbar-nav .nav-link.disabled {
           color: rgba(0, 0, 0, .3)
       }
       
       .navbar-light .navbar-nav .active>.nav-link,
       .navbar-light .navbar-nav .nav-link.active,
       .navbar-light .navbar-nav .nav-link.show,
       .navbar-light .navbar-nav .show>.nav-link {
           color: rgba(0, 0, 0, .9)
       }
       
       .navbar-light .navbar-toggler {
           color: rgba(0, 0, 0, .5);
           border-color: rgba(0, 0, 0, .1)
       }
       
       .navbar-light .navbar-toggler-icon {
           background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E")
       }
       
       .navbar-light .navbar-text {
           color: rgba(0, 0, 0, .5)
       }
       
       .navbar-light .navbar-text a {
           color: rgba(0, 0, 0, .9)
       }
       
       .navbar-light .navbar-text a:focus,
       .navbar-light .navbar-text a:hover {
           color: rgba(0, 0, 0, .9)
       }
       
       .navbar-dark .navbar-brand {
           color: #fff
       }
       
       .navbar-dark .navbar-brand:focus,
       .navbar-dark .navbar-brand:hover {
           color: #fff
       }
       
       .navbar-dark .navbar-nav .nav-link {
           color: rgba(255, 255, 255, .5)
       }
       
       .navbar-dark .navbar-nav .nav-link:focus,
       .navbar-dark .navbar-nav .nav-link:hover {
           color: rgba(255, 255, 255, .75)
       }
       
       .navbar-dark .navbar-nav .nav-link.disabled {
           color: rgba(255, 255, 255, .25)
       }
       
       .navbar-dark .navbar-nav .active>.nav-link,
       .navbar-dark .navbar-nav .nav-link.active,
       .navbar-dark .navbar-nav .nav-link.show,
       .navbar-dark .navbar-nav .show>.nav-link {
           color: #fff
       }
       
       .navbar-dark .navbar-toggler {
           color: rgba(255, 255, 255, .5);
           border-color: rgba(255, 255, 255, .1)
       }
       
       .navbar-dark .navbar-toggler-icon {
           background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E")
       }
       
       .navbar-dark .navbar-text {
           color: rgba(255, 255, 255, .5)
       }
       
       .navbar-dark .navbar-text a {
           color: #fff
       }
       
       .navbar-dark .navbar-text a:focus,
       .navbar-dark .navbar-text a:hover {
           color: #fff
       }
       
       .card {
           position: relative;
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column;
           min-width: 0;
           word-wrap: break-word;
           background-color: #fff;
           background-clip: border-box;
           border: 1px solid rgba(0, 0, 0, .125);
           border-radius: .25rem
       }
       
       .card>hr {
           margin-right: 0;
           margin-left: 0
       }
       
       .card>.list-group:first-child .list-group-item:first-child {
           border-top-left-radius: .25rem;
           border-top-right-radius: .25rem
       }
       
       .card>.list-group:last-child .list-group-item:last-child {
           border-bottom-right-radius: .25rem;
           border-bottom-left-radius: .25rem
       }
       
       .card-body {
           -webkit-box-flex: 1;
           -ms-flex: 1 1 auto;
           flex: 1 1 auto;
           padding: 1.25rem
       }
       
       .card-title {
           margin-bottom: .75rem
       }
       
       .card-subtitle {
           margin-top: -.375rem;
           margin-bottom: 0
       }
       
       .card-text:last-child {
           margin-bottom: 0
       }
       
       .card-link:hover {
           text-decoration: none
       }
       
       .card-link+.card-link {
           margin-left: 1.25rem
       }
       
       .card-header {
           padding: .75rem 1.25rem;
           margin-bottom: 0;
           background-color: rgba(0, 0, 0, .03);
           border-bottom: 1px solid rgba(0, 0, 0, .125)
       }
       
       .card-header:first-child {
           border-radius: calc(.25rem - 1px) calc(.25rem - 1px) 0 0
       }
       
       .card-header+.list-group .list-group-item:first-child {
           border-top: 0
       }
       
       .card-footer {
           padding: .75rem 1.25rem;
           background-color: rgba(0, 0, 0, .03);
           border-top: 1px solid rgba(0, 0, 0, .125)
       }
       
       .card-footer:last-child {
           border-radius: 0 0 calc(.25rem - 1px) calc(.25rem - 1px)
       }
       
       .card-header-tabs {
           margin-right: -.625rem;
           margin-bottom: -.75rem;
           margin-left: -.625rem;
           border-bottom: 0
       }
       
       .card-header-pills {
           margin-right: -.625rem;
           margin-left: -.625rem
       }
       
       .card-img-overlay {
           position: absolute;
           top: 0;
           right: 0;
           bottom: 0;
           left: 0;
           padding: 1.25rem
       }
       
       .card-img {
           width: 100%;
           border-radius: calc(.25rem - 1px)
       }
       
       .card-img-top {
           width: 100%;
           border-top-left-radius: calc(.25rem - 1px);
           border-top-right-radius: calc(.25rem - 1px)
       }
       
       .card-img-bottom {
           width: 100%;
           border-bottom-right-radius: calc(.25rem - 1px);
           border-bottom-left-radius: calc(.25rem - 1px)
       }
       
       .card-deck {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column
       }
       
       .card-deck .card {
           margin-bottom: 15px
       }
       
       @media (min-width:576px) {
           .card-deck {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-flow: row wrap;
               flex-flow: row wrap;
               margin-right: -15px;
               margin-left: -15px
           }
           .card-deck .card {
               display: -webkit-box;
               display: -ms-flexbox;
               display: flex;
               -webkit-box-flex: 1;
               -ms-flex: 1 0 0%;
               flex: 1 0 0%;
               -webkit-box-orient: vertical;
               -webkit-box-direction: normal;
               -ms-flex-direction: column;
               flex-direction: column;
               margin-right: 15px;
               margin-bottom: 0;
               margin-left: 15px
           }
       }
       
       .card-group {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column
       }
       
       .card-group>.card {
           margin-bottom: 15px
       }
       
       @media (min-width:576px) {
           .card-group {
               -webkit-box-orient: horizontal;
               -webkit-box-direction: normal;
               -ms-flex-flow: row wrap;
               flex-flow: row wrap
           }
           .card-group>.card {
               -webkit-box-flex: 1;
               -ms-flex: 1 0 0%;
               flex: 1 0 0%;
               margin-bottom: 0
           }
           .card-group>.card+.card {
               margin-left: 0;
               border-left: 0
           }
           .card-group>.card:first-child {
               border-top-right-radius: 0;
               border-bottom-right-radius: 0
           }
           .card-group>.card:first-child .card-header,
           .card-group>.card:first-child .card-img-top {
               border-top-right-radius: 0
           }
           .card-group>.card:first-child .card-footer,
           .card-group>.card:first-child .card-img-bottom {
               border-bottom-right-radius: 0
           }
           .card-group>.card:last-child {
               border-top-left-radius: 0;
               border-bottom-left-radius: 0
           }
           .card-group>.card:last-child .card-header,
           .card-group>.card:last-child .card-img-top {
               border-top-left-radius: 0
           }
           .card-group>.card:last-child .card-footer,
           .card-group>.card:last-child .card-img-bottom {
               border-bottom-left-radius: 0
           }
           .card-group>.card:only-child {
               border-radius: .25rem
           }
           .card-group>.card:only-child .card-header,
           .card-group>.card:only-child .card-img-top {
               border-top-left-radius: .25rem;
               border-top-right-radius: .25rem
           }
           .card-group>.card:only-child .card-footer,
           .card-group>.card:only-child .card-img-bottom {
               border-bottom-right-radius: .25rem;
               border-bottom-left-radius: .25rem
           }
           .card-group>.card:not(:first-child):not(:last-child):not(:only-child) {
               border-radius: 0
           }
           .card-group>.card:not(:first-child):not(:last-child):not(:only-child) .card-footer,
           .card-group>.card:not(:first-child):not(:last-child):not(:only-child) .card-header,
           .card-group>.card:not(:first-child):not(:last-child):not(:only-child) .card-img-bottom,
           .card-group>.card:not(:first-child):not(:last-child):not(:only-child) .card-img-top {
               border-radius: 0
           }
       }
       
       .card-columns .card {
           margin-bottom: .75rem
       }
       
       @media (min-width:576px) {
           .card-columns {
               -webkit-column-count: 3;
               -moz-column-count: 3;
               column-count: 3;
               -webkit-column-gap: 1.25rem;
               -moz-column-gap: 1.25rem;
               column-gap: 1.25rem
           }
           .card-columns .card {
               display: inline-block;
               width: 100%
           }
       }
       
       .breadcrumb {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -ms-flex-wrap: wrap;
           flex-wrap: wrap;
           padding: .75rem 1rem;
           margin-bottom: 1rem;
           list-style: none;
           background-color: #e9ecef;
           border-radius: .25rem
       }
       
       .breadcrumb-item+.breadcrumb-item::before {
           display: inline-block;
           padding-right: .5rem;
           padding-left: .5rem;
           color: #6c757d;
           content: "/"
       }
       
       .breadcrumb-item+.breadcrumb-item:hover::before {
           text-decoration: underline
       }
       
       .breadcrumb-item+.breadcrumb-item:hover::before {
           text-decoration: none
       }
       
       .breadcrumb-item.active {
           color: #6c757d
       }
       
       .pagination {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           padding-left: 0;
           list-style: none;
           border-radius: .25rem
       }
       
       .page-link {
           position: relative;
           display: block;
           padding: .5rem .75rem;
           margin-left: -1px;
           line-height: 1.25;
           color: #007bff;
           background-color: #fff;
           border: 1px solid #dee2e6
       }
       
       .page-link:hover {
           color: #0056b3;
           text-decoration: none;
           background-color: #e9ecef;
           border-color: #dee2e6
       }
       
       .page-link:focus {
           z-index: 2;
           outline: 0;
           box-shadow: 0 0 0 .2rem rgba(0, 123, 255, .25)
       }
       
       .page-link:not(:disabled):not(.disabled) {
           cursor: pointer
       }
       
       .page-item:first-child .page-link {
           margin-left: 0;
           border-top-left-radius: .25rem;
           border-bottom-left-radius: .25rem
       }
       
       .page-item:last-child .page-link {
           border-top-right-radius: .25rem;
           border-bottom-right-radius: .25rem
       }
       
       .page-item.active .page-link {
           z-index: 1;
           color: #fff;
           background-color: #007bff;
           border-color: #007bff
       }
       
       .page-item.disabled .page-link {
           color: #6c757d;
           pointer-events: none;
           cursor: auto;
           background-color: #fff;
           border-color: #dee2e6
       }
       
       .pagination-lg .page-link {
           padding: .75rem 1.5rem;
           font-size: 1.25rem;
           line-height: 1.5
       }
       
       .pagination-lg .page-item:first-child .page-link {
           border-top-left-radius: .3rem;
           border-bottom-left-radius: .3rem
       }
       
       .pagination-lg .page-item:last-child .page-link {
           border-top-right-radius: .3rem;
           border-bottom-right-radius: .3rem
       }
       
       .pagination-sm .page-link {
           padding: .25rem .5rem;
           font-size: .875rem;
           line-height: 1.5
       }
       
       .pagination-sm .page-item:first-child .page-link {
           border-top-left-radius: .2rem;
           border-bottom-left-radius: .2rem
       }
       
       .pagination-sm .page-item:last-child .page-link {
           border-top-right-radius: .2rem;
           border-bottom-right-radius: .2rem
       }
       
       .badge {
           display: inline-block;
           padding: .25em .4em;
           font-size: 75%;
           font-weight: 700;
           line-height: 1;
           text-align: center;
           white-space: nowrap;
           vertical-align: baseline;
           border-radius: .25rem
       }
       
       .badge:empty {
           display: none
       }
       
       .btn .badge {
           position: relative;
           top: -1px
       }
       
       .badge-pill {
           padding-right: .6em;
           padding-left: .6em;
           border-radius: 10rem
       }
       
       .badge-primary {
           color: #fff;
           background-color: #007bff
       }
       
       .badge-primary[href]:focus,
       .badge-primary[href]:hover {
           color: #fff;
           text-decoration: none;
           background-color: #0062cc
       }
       
       .badge-secondary {
           color: #fff;
           background-color: #6c757d
       }
       
       .badge-secondary[href]:focus,
       .badge-secondary[href]:hover {
           color: #fff;
           text-decoration: none;
           background-color: #545b62
       }
       
       .badge-success {
           color: #fff;
           background-color: #28a745
       }
       
       .badge-success[href]:focus,
       .badge-success[href]:hover {
           color: #fff;
           text-decoration: none;
           background-color: #1e7e34
       }
       
       .badge-info {
           color: #fff;
           background-color: #17a2b8
       }
       
       .badge-info[href]:focus,
       .badge-info[href]:hover {
           color: #fff;
           text-decoration: none;
           background-color: #117a8b
       }
       
       .badge-warning {
           color: #212529;
           background-color: #ffc107
       }
       
       .badge-warning[href]:focus,
       .badge-warning[href]:hover {
           color: #212529;
           text-decoration: none;
           background-color: #d39e00
       }
       
       .badge-danger {
           color: #fff;
           background-color: #dc3545
       }
       
       .badge-danger[href]:focus,
       .badge-danger[href]:hover {
           color: #fff;
           text-decoration: none;
           background-color: #bd2130
       }
       
       .badge-light {
           color: #212529;
           background-color: #f8f9fa
       }
       
       .badge-light[href]:focus,
       .badge-light[href]:hover {
           color: #212529;
           text-decoration: none;
           background-color: #dae0e5
       }
       
       .badge-dark {
           color: #fff;
           background-color: #343a40
       }
       
       .badge-dark[href]:focus,
       .badge-dark[href]:hover {
           color: #fff;
           text-decoration: none;
           background-color: #1d2124
       }
       
       .jumbotron {
           padding: 2rem 1rem;
           margin-bottom: 2rem;
           background-color: #e9ecef;
           border-radius: .3rem
       }
       
       @media (min-width:576px) {
           .jumbotron {
               padding: 4rem 2rem
           }
       }
       
       .jumbotron-fluid {
           padding-right: 0;
           padding-left: 0;
           border-radius: 0
       }
       
       .alert {
           position: relative;
           padding: .75rem 1.25rem;
           margin-bottom: 1rem;
           border: 1px solid transparent;
           border-radius: .25rem
       }
       
       .alert-heading {
           color: inherit
       }
       
       .alert-link {
           font-weight: 700
       }
       
       .alert-dismissible {
           padding-right: 4rem
       }
       
       .alert-dismissible .close {
           position: absolute;
           top: 0;
           right: 0;
           padding: .75rem 1.25rem;
           color: inherit
       }
       
       .alert-primary {
           color: #004085;
           background-color: #cce5ff;
           border-color: #b8daff
       }
       
       .alert-primary hr {
           border-top-color: #9fcdff
       }
       
       .alert-primary .alert-link {
           color: #002752
       }
       
       .alert-secondary {
           color: #383d41;
           background-color: #e2e3e5;
           border-color: #d6d8db
       }
       
       .alert-secondary hr {
           border-top-color: #c8cbcf
       }
       
       .alert-secondary .alert-link {
           color: #202326
       }
       
       .alert-success {
           color: #155724;
           background-color: #d4edda;
           border-color: #c3e6cb
       }
       
       .alert-success hr {
           border-top-color: #b1dfbb
       }
       
       .alert-success .alert-link {
           color: #0b2e13
       }
       
       .alert-info {
           color: #0c5460;
           background-color: #d1ecf1;
           border-color: #bee5eb
       }
       
       .alert-info hr {
           border-top-color: #abdde5
       }
       
       .alert-info .alert-link {
           color: #062c33
       }
       
       .alert-warning {
           color: #856404;
           background-color: #fff3cd;
           border-color: #ffeeba
       }
       
       .alert-warning hr {
           border-top-color: #ffe8a1
       }
       
       .alert-warning .alert-link {
           color: #533f03
       }
       
       .alert-danger {
           color: #721c24;
           background-color: #f8d7da;
           border-color: #f5c6cb
       }
       
       .alert-danger hr {
           border-top-color: #f1b0b7
       }
       
       .alert-danger .alert-link {
           color: #491217
       }
       
       .alert-light {
           color: #818182;
           background-color: #fefefe;
           border-color: #fdfdfe
       }
       
       .alert-light hr {
           border-top-color: #ececf6
       }
       
       .alert-light .alert-link {
           color: #686868
       }
       
       .alert-dark {
           color: #1b1e21;
           background-color: #d6d8d9;
           border-color: #c6c8ca
       }
       
       .alert-dark hr {
           border-top-color: #b9bbbe
       }
       
       .alert-dark .alert-link {
           color: #040505
       }
       
       @-webkit-keyframes progress-bar-stripes {
           from {
               background-position: 1rem 0
           }
           to {
               background-position: 0 0
           }
       }
       
       @keyframes progress-bar-stripes {
           from {
               background-position: 1rem 0
           }
           to {
               background-position: 0 0
           }
       }
       
       .progress {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           height: 1rem;
           overflow: hidden;
           font-size: .75rem;
           background-color: #e9ecef;
           border-radius: .25rem
       }
       
       .progress-bar {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column;
           -webkit-box-pack: center;
           -ms-flex-pack: center;
           justify-content: center;
           color: #fff;
           text-align: center;
           background-color: #007bff;
           transition: width .6s ease
       }
       
       .progress-bar-striped {
           background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
           background-size: 1rem 1rem
       }
       
       .progress-bar-animated {
           -webkit-animation: progress-bar-stripes 1s linear infinite;
           animation: progress-bar-stripes 1s linear infinite
       }
       
       .media {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-align: start;
           -ms-flex-align: start;
           align-items: flex-start
       }
       
       .media-body {
           -webkit-box-flex: 1;
           -ms-flex: 1;
           flex: 1
       }
       
       .list-group {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column;
           padding-left: 0;
           margin-bottom: 0
       }
       
       .list-group-item-action {
           width: 100%;
           color: #495057;
           text-align: inherit
       }
       
       .list-group-item-action:focus,
       .list-group-item-action:hover {
           color: #495057;
           text-decoration: none;
           background-color: #f8f9fa
       }
       
       .list-group-item-action:active {
           color: #212529;
           background-color: #e9ecef
       }
       
       .list-group-item {
           position: relative;
           display: block;
           padding: .75rem 1.25rem;
           margin-bottom: -1px;
           background-color: #fff;
           border: 1px solid rgba(0, 0, 0, .125)
       }
       
       .list-group-item:first-child {
           border-top-left-radius: .25rem;
           border-top-right-radius: .25rem
       }
       
       .list-group-item:last-child {
           margin-bottom: 0;
           border-bottom-right-radius: .25rem;
           border-bottom-left-radius: .25rem
       }
       
       .list-group-item:focus,
       .list-group-item:hover {
           z-index: 1;
           text-decoration: none
       }
       
       .list-group-item.disabled,
       .list-group-item:disabled {
           color: #6c757d;
           background-color: #fff
       }
       
       .list-group-item.active {
           z-index: 2;
           color: #fff;
           background-color: #007bff;
           border-color: #007bff
       }
       
       .list-group-flush .list-group-item {
           border-right: 0;
           border-left: 0;
           border-radius: 0
       }
       
       .list-group-flush:first-child .list-group-item:first-child {
           border-top: 0
       }
       
       .list-group-flush:last-child .list-group-item:last-child {
           border-bottom: 0
       }
       
       .list-group-item-primary {
           color: #004085;
           background-color: #b8daff
       }
       
       .list-group-item-primary.list-group-item-action:focus,
       .list-group-item-primary.list-group-item-action:hover {
           color: #004085;
           background-color: #9fcdff
       }
       
       .list-group-item-primary.list-group-item-action.active {
           color: #fff;
           background-color: #004085;
           border-color: #004085
       }
       
       .list-group-item-secondary {
           color: #383d41;
           background-color: #d6d8db
       }
       
       .list-group-item-secondary.list-group-item-action:focus,
       .list-group-item-secondary.list-group-item-action:hover {
           color: #383d41;
           background-color: #c8cbcf
       }
       
       .list-group-item-secondary.list-group-item-action.active {
           color: #fff;
           background-color: #383d41;
           border-color: #383d41
       }
       
       .list-group-item-success {
           color: #155724;
           background-color: #c3e6cb
       }
       
       .list-group-item-success.list-group-item-action:focus,
       .list-group-item-success.list-group-item-action:hover {
           color: #155724;
           background-color: #b1dfbb
       }
       
       .list-group-item-success.list-group-item-action.active {
           color: #fff;
           background-color: #155724;
           border-color: #155724
       }
       
       .list-group-item-info {
           color: #0c5460;
           background-color: #bee5eb
       }
       
       .list-group-item-info.list-group-item-action:focus,
       .list-group-item-info.list-group-item-action:hover {
           color: #0c5460;
           background-color: #abdde5
       }
       
       .list-group-item-info.list-group-item-action.active {
           color: #fff;
           background-color: #0c5460;
           border-color: #0c5460
       }
       
       .list-group-item-warning {
           color: #856404;
           background-color: #ffeeba
       }
       
       .list-group-item-warning.list-group-item-action:focus,
       .list-group-item-warning.list-group-item-action:hover {
           color: #856404;
           background-color: #ffe8a1
       }
       
       .list-group-item-warning.list-group-item-action.active {
           color: #fff;
           background-color: #856404;
           border-color: #856404
       }
       
       .list-group-item-danger {
           color: #721c24;
           background-color: #f5c6cb
       }
       
       .list-group-item-danger.list-group-item-action:focus,
       .list-group-item-danger.list-group-item-action:hover {
           color: #721c24;
           background-color: #f1b0b7
       }
       
       .list-group-item-danger.list-group-item-action.active {
           color: #fff;
           background-color: #721c24;
           border-color: #721c24
       }
       
       .list-group-item-light {
           color: #818182;
           background-color: #fdfdfe
       }
       
       .list-group-item-light.list-group-item-action:focus,
       .list-group-item-light.list-group-item-action:hover {
           color: #818182;
           background-color: #ececf6
       }
       
       .list-group-item-light.list-group-item-action.active {
           color: #fff;
           background-color: #818182;
           border-color: #818182
       }
       
       .list-group-item-dark {
           color: #1b1e21;
           background-color: #c6c8ca
       }
       
       .list-group-item-dark.list-group-item-action:focus,
       .list-group-item-dark.list-group-item-action:hover {
           color: #1b1e21;
           background-color: #b9bbbe
       }
       
       .list-group-item-dark.list-group-item-action.active {
           color: #fff;
           background-color: #1b1e21;
           border-color: #1b1e21
       }
       
       .close {
           float: right;
           font-size: 1.5rem;
           font-weight: 700;
           line-height: 1;
           color: #000;
           text-shadow: 0 1px 0 #fff;
           opacity: .5
       }
       
       .close:focus,
       .close:hover {
           color: #000;
           text-decoration: none;
           opacity: .75
       }
       
       .close:not(:disabled):not(.disabled) {
           cursor: pointer
       }
       
       button.close {
           padding: 0;
           background-color: transparent;
           border: 0;
           -webkit-appearance: none
       }
       
       .modal-open {
           overflow: hidden
       }
       
       .modal {
           position: fixed;
           top: 0;
           right: 0;
           bottom: 0;
           left: 0;
           z-index: 1050;
           display: none;
           overflow: hidden;
           outline: 0
       }
       
       .modal-open .modal {
           overflow-x: hidden;
           overflow-y: auto
       }
       
       .modal-dialog {
           position: relative;
           width: auto;
           margin: .5rem;
           pointer-events: none
       }
       
       .modal.fade .modal-dialog {
           transition: -webkit-transform .3s ease-out;
           transition: transform .3s ease-out;
           transition: transform .3s ease-out, -webkit-transform .3s ease-out;
           -webkit-transform: translate(0, -25%);
           transform: translate(0, -25%)
       }
       
       .modal.show .modal-dialog {
           -webkit-transform: translate(0, 0);
           transform: translate(0, 0)
       }
       
       .modal-dialog-centered {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           min-height: calc(100% - (.5rem * 2))
       }
       
       .modal-content {
           position: relative;
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-orient: vertical;
           -webkit-box-direction: normal;
           -ms-flex-direction: column;
           flex-direction: column;
           width: 100%;
           pointer-events: auto;
           background-color: #fff;
           background-clip: padding-box;
           border-radius: .3rem;
           outline: 0
       }
       
       .modal-backdrop {
           position: fixed;
           top: 0;
           right: 0;
           bottom: 0;
           left: 0;
           z-index: 999999;
           background-color: #000
       }
       
       .modal-backdrop.fade {
           opacity: 0
       }
       
       .modal-backdrop.show {
           opacity: .5
       }
       
       .modal-header {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-align: start;
           -ms-flex-align: start;
           align-items: flex-start;
           -webkit-box-pack: justify;
           -ms-flex-pack: justify;
           justify-content: space-between;
           padding: 1rem;
           border-bottom: 1px solid #e9ecef;
           border-top-left-radius: .3rem;
           border-top-right-radius: .3rem
       }
       
       .modal-header .close {
           padding: 1rem;
           margin: -1rem -1rem -1rem auto
       }
       
       .modal-title {
           margin-bottom: 0;
           line-height: 1.5
       }
       
       .modal-body {
           position: relative;
           -webkit-box-flex: 1;
           -ms-flex: 1 1 auto;
           flex: 1 1 auto;
           padding: 1rem
       }
       
       .modal-footer {
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           -webkit-box-pack: end;
           -ms-flex-pack: end;
           justify-content: flex-end;
           padding: 1rem;
           border-top: 1px solid #e9ecef
       }
       
       .modal-footer>:not(:first-child) {
           margin-left: .25rem
       }
       
       .modal-footer>:not(:last-child) {
           margin-right: .25rem
       }
       
       .modal-scrollbar-measure {
           position: absolute;
           top: -9999px;
           width: 50px;
           height: 50px;
           overflow: scroll
       }
       
       @media (min-width:576px) {
           .modal-dialog {
               max-width: 500px;
               margin: 1.75rem auto
           }
           .modal-dialog-centered {
               min-height: calc(100% - (1.75rem * 2))
           }
           .modal-sm {
               max-width: 300px
           }
       }
       
       @media (min-width:992px) {
           .modal-lg {
               max-width: 800px
           }
       }
       
       .tooltip {
           position: absolute;
           z-index: 1070;
           display: block;
           margin: 0;
           font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
           font-style: normal;
           font-weight: 400;
           line-height: 1.5;
           text-align: left;
           text-align: start;
           text-decoration: none;
           text-shadow: none;
           text-transform: none;
           letter-spacing: normal;
           word-break: normal;
           word-spacing: normal;
           white-space: normal;
           line-break: auto;
           font-size: .875rem;
           word-wrap: break-word;
           opacity: 0
       }
       
       .tooltip.show {
           opacity: .9
       }
       
       .tooltip .arrow {
           position: absolute;
           display: block;
           width: .8rem;
           height: .4rem
       }
       
       .tooltip .arrow::before {
           position: absolute;
           content: "";
           border-color: transparent;
           border-style: solid
       }
       
       .bs-tooltip-auto[x-placement^=top],
       .bs-tooltip-top {
           padding: .4rem 0
       }
       
       .bs-tooltip-auto[x-placement^=top] .arrow,
       .bs-tooltip-top .arrow {
           bottom: 0
       }
       
       .bs-tooltip-auto[x-placement^=top] .arrow::before,
       .bs-tooltip-top .arrow::before {
           top: 0;
           border-width: .4rem .4rem 0;
           border-top-color: #000
       }
       
       .bs-tooltip-auto[x-placement^=right],
       .bs-tooltip-right {
           padding: 0 .4rem
       }
       
       .bs-tooltip-auto[x-placement^=right] .arrow,
       .bs-tooltip-right .arrow {
           left: 0;
           width: .4rem;
           height: .8rem
       }
       
       .bs-tooltip-auto[x-placement^=right] .arrow::before,
       .bs-tooltip-right .arrow::before {
           right: 0;
           border-width: .4rem .4rem .4rem 0;
           border-right-color: #000
       }
       
       .bs-tooltip-auto[x-placement^=bottom],
       .bs-tooltip-bottom {
           padding: .4rem 0
       }
       
       .bs-tooltip-auto[x-placement^=bottom] .arrow,
       .bs-tooltip-bottom .arrow {
           top: 0
       }
       
       .bs-tooltip-auto[x-placement^=bottom] .arrow::before,
       .bs-tooltip-bottom .arrow::before {
           bottom: 0;
           border-width: 0 .4rem .4rem;
           border-bottom-color: #000
       }
       
       .bs-tooltip-auto[x-placement^=left],
       .bs-tooltip-left {
           padding: 0 .4rem
       }
       
       .bs-tooltip-auto[x-placement^=left] .arrow,
       .bs-tooltip-left .arrow {
           right: 0;
           width: .4rem;
           height: .8rem
       }
       
       .bs-tooltip-auto[x-placement^=left] .arrow::before,
       .bs-tooltip-left .arrow::before {
           left: 0;
           border-width: .4rem 0 .4rem .4rem;
           border-left-color: #000
       }
       
       .tooltip-inner {
           max-width: 200px;
           padding: .25rem .5rem;
           color: #fff;
           text-align: center;
           background-color: #000;
           border-radius: .25rem
       }
       
       .popover {
           position: absolute;
           top: 0;
           left: 0;
           z-index: 1060;
           display: block;
           max-width: 276px;
           font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
           font-style: normal;
           font-weight: 400;
           line-height: 1.5;
           text-align: left;
           text-align: start;
           text-decoration: none;
           text-shadow: none;
           text-transform: none;
           letter-spacing: normal;
           word-break: normal;
           word-spacing: normal;
           white-space: normal;
           line-break: auto;
           font-size: .875rem;
           word-wrap: break-word;
           background-color: #fff;
           background-clip: padding-box;
           border: 1px solid rgba(0, 0, 0, .2);
           border-radius: .3rem
       }
       
       .popover .arrow {
           position: absolute;
           display: block;
           width: 1rem;
           height: .5rem;
           margin: 0 .3rem
       }
       
       .popover .arrow::after,
       .popover .arrow::before {
           position: absolute;
           display: block;
           content: "";
           border-color: transparent;
           border-style: solid
       }
       
       .bs-popover-auto[x-placement^=top],
       .bs-popover-top {
           margin-bottom: .5rem
       }
       
       .bs-popover-auto[x-placement^=top] .arrow,
       .bs-popover-top .arrow {
           bottom: calc((.5rem + 1px) * -1)
       }
       
       .bs-popover-auto[x-placement^=top] .arrow::after,
       .bs-popover-auto[x-placement^=top] .arrow::before,
       .bs-popover-top .arrow::after,
       .bs-popover-top .arrow::before {
           border-width: .5rem .5rem 0
       }
       
       .bs-popover-auto[x-placement^=top] .arrow::before,
       .bs-popover-top .arrow::before {
           bottom: 0;
           border-top-color: rgba(0, 0, 0, .25)
       }
       
       .bs-popover-auto[x-placement^=top] .arrow::after,
       .bs-popover-top .arrow::after {
           bottom: 1px;
           border-top-color: #fff
       }
       
       .bs-popover-auto[x-placement^=right],
       .bs-popover-right {
           margin-left: .5rem
       }
       
       .bs-popover-auto[x-placement^=right] .arrow,
       .bs-popover-right .arrow {
           left: calc((.5rem + 1px) * -1);
           width: .5rem;
           height: 1rem;
           margin: .3rem 0
       }
       
       .bs-popover-auto[x-placement^=right] .arrow::after,
       .bs-popover-auto[x-placement^=right] .arrow::before,
       .bs-popover-right .arrow::after,
       .bs-popover-right .arrow::before {
           border-width: .5rem .5rem .5rem 0
       }
       
       .bs-popover-auto[x-placement^=right] .arrow::before,
       .bs-popover-right .arrow::before {
           left: 0;
           border-right-color: rgba(0, 0, 0, .25)
       }
       
       .bs-popover-auto[x-placement^=right] .arrow::after,
       .bs-popover-right .arrow::after {
           left: 1px;
           border-right-color: #fff
       }
       
       .bs-popover-auto[x-placement^=bottom],
       .bs-popover-bottom {
           margin-top: .5rem
       }
       
       .bs-popover-auto[x-placement^=bottom] .arrow,
       .bs-popover-bottom .arrow {
           top: calc((.5rem + 1px) * -1)
       }
       
       .bs-popover-auto[x-placement^=bottom] .arrow::after,
       .bs-popover-auto[x-placement^=bottom] .arrow::before,
       .bs-popover-bottom .arrow::after,
       .bs-popover-bottom .arrow::before {
           border-width: 0 .5rem .5rem .5rem
       }
       
       .bs-popover-auto[x-placement^=bottom] .arrow::before,
       .bs-popover-bottom .arrow::before {
           top: 0;
           border-bottom-color: rgba(0, 0, 0, .25)
       }
       
       .bs-popover-auto[x-placement^=bottom] .arrow::after,
       .bs-popover-bottom .arrow::after {
           top: 1px;
           border-bottom-color: #fff
       }
       
       .bs-popover-auto[x-placement^=bottom] .popover-header::before,
       .bs-popover-bottom .popover-header::before {
           position: absolute;
           top: 0;
           left: 50%;
           display: block;
           width: 1rem;
           margin-left: -.5rem;
           content: "";
           border-bottom: 1px solid #f7f7f7
       }
       
       .bs-popover-auto[x-placement^=left],
       .bs-popover-left {
           margin-right: .5rem
       }
       
       .bs-popover-auto[x-placement^=left] .arrow,
       .bs-popover-left .arrow {
           right: calc((.5rem + 1px) * -1);
           width: .5rem;
           height: 1rem;
           margin: .3rem 0
       }
       
       .bs-popover-auto[x-placement^=left] .arrow::after,
       .bs-popover-auto[x-placement^=left] .arrow::before,
       .bs-popover-left .arrow::after,
       .bs-popover-left .arrow::before {
           border-width: .5rem 0 .5rem .5rem
       }
       
       .bs-popover-auto[x-placement^=left] .arrow::before,
       .bs-popover-left .arrow::before {
           right: 0;
           border-left-color: rgba(0, 0, 0, .25)
       }
       
       .bs-popover-auto[x-placement^=left] .arrow::after,
       .bs-popover-left .arrow::after {
           right: 1px;
           border-left-color: #fff
       }
       
       .popover-header {
           padding: .5rem .75rem;
           margin-bottom: 0;
           font-size: 1rem;
           color: inherit;
           background-color: #f7f7f7;
           border-bottom: 1px solid #ebebeb;
           border-top-left-radius: calc(.3rem - 1px);
           border-top-right-radius: calc(.3rem - 1px)
       }
       
       .popover-header:empty {
           display: none
       }
       
       .popover-body {
           padding: .5rem .75rem;
           color: #212529
       }
       
       .carousel {
           position: relative
       }
       
       .carousel-inner {
           position: relative;
           width: 100%;
           overflow: hidden
       }
       
       .carousel-item {
           position: relative;
           display: none;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           width: 100%;
           transition: -webkit-transform .6s ease;
           transition: transform .6s ease;
           transition: transform .6s ease, -webkit-transform .6s ease;
           -webkit-backface-visibility: hidden;
           backface-visibility: hidden;
           -webkit-perspective: 1000px;
           perspective: 1000px
       }
       
       .carousel-item-next,
       .carousel-item-prev,
       .carousel-item.active {
           display: block
       }
       
       .carousel-item-next,
       .carousel-item-prev {
           position: absolute;
           top: 0
       }
       
       .carousel-item-next.carousel-item-left,
       .carousel-item-prev.carousel-item-right {
           -webkit-transform: translateX(0);
           transform: translateX(0)
       }
       
       @supports ((-webkit-transform-style:preserve-3d) or (transform-style:preserve-3d)) {
           .carousel-item-next.carousel-item-left,
           .carousel-item-prev.carousel-item-right {
               -webkit-transform: translate3d(0, 0, 0);
               transform: translate3d(0, 0, 0)
           }
       }
       
       .active.carousel-item-right,
       .carousel-item-next {
           -webkit-transform: translateX(100%);
           transform: translateX(100%)
       }
       
       @supports ((-webkit-transform-style:preserve-3d) or (transform-style:preserve-3d)) {
           .active.carousel-item-right,
           .carousel-item-next {
               -webkit-transform: translate3d(100%, 0, 0);
               transform: translate3d(100%, 0, 0)
           }
       }
       
       .active.carousel-item-left,
       .carousel-item-prev {
           -webkit-transform: translateX(-100%);
           transform: translateX(-100%)
       }
       
       @supports ((-webkit-transform-style:preserve-3d) or (transform-style:preserve-3d)) {
           .active.carousel-item-left,
           .carousel-item-prev {
               -webkit-transform: translate3d(-100%, 0, 0);
               transform: translate3d(-100%, 0, 0)
           }
       }
       
       .carousel-control-next,
       .carousel-control-prev {
           position: absolute;
           top: 0;
           bottom: 0;
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-align: center;
           -ms-flex-align: center;
           align-items: center;
           -webkit-box-pack: center;
           -ms-flex-pack: center;
           justify-content: center;
           width: 15%;
           color: #fff;
           text-align: center;
           opacity: .5
       }
       
       .carousel-control-next:focus,
       .carousel-control-next:hover,
       .carousel-control-prev:focus,
       .carousel-control-prev:hover {
           color: #fff;
           text-decoration: none;
           outline: 0;
           opacity: .9
       }
       
       .carousel-control-prev {
           left: 0
       }
       
       .carousel-control-next {
           right: 0
       }
       
       .carousel-control-next-icon,
       .carousel-control-prev-icon {
           display: inline-block;
           width: 20px;
           height: 20px;
           background: transparent no-repeat center center;
           background-size: 100% 100%
       }
       
       .carousel-control-prev-icon {
           background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E")
       }
       
       .carousel-control-next-icon {
           background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E")
       }
       
       .carousel-indicators {
           position: absolute;
           right: 0;
           bottom: 10px;
           left: 0;
           z-index: 15;
           display: -webkit-box;
           display: -ms-flexbox;
           display: flex;
           -webkit-box-pack: center;
           -ms-flex-pack: center;
           justify-content: center;
           padding-left: 0;
           margin-right: 15%;
           margin-left: 15%;
           list-style: none
       }
       
       .carousel-indicators li {
           position: relative;
           -webkit-box-flex: 0;
           -ms-flex: 0 1 auto;
           flex: 0 1 auto;
           width: 30px;
           height: 3px;
           margin-right: 3px;
           margin-left: 3px;
           text-indent: -999px;
           background-color: rgba(255, 255, 255, .5)
       }
       
       .carousel-indicators li::before {
           position: absolute;
           top: -10px;
           left: 0;
           display: inline-block;
           width: 100%;
           height: 10px;
           content: ""
       }
       
       .carousel-indicators li::after {
           position: absolute;
           bottom: -10px;
           left: 0;
           display: inline-block;
           width: 100%;
           height: 10px;
           content: ""
       }
       
       .carousel-indicators .active {
           background-color: #fff
       }
       
       .carousel-caption {
           position: absolute;
           right: 15%;
           bottom: 20px;
           left: 15%;
           z-index: 10;
           padding-top: 20px;
           padding-bottom: 20px;
           color: #fff;
           text-align: center
       }
       
       .align-baseline {
           vertical-align: baseline!important
       }
       
       .align-top {
           vertical-align: top!important
       }
       
       .align-middle {
           vertical-align: middle!important
       }
       
       .align-bottom {
           vertical-align: bottom!important
       }
       
       .align-text-bottom {
           vertical-align: text-bottom!important
       }
       
       .align-text-top {
           vertical-align: text-top!important
       }
       
       .bg-primary {
           background-color: #007bff!important
       }
       
       a.bg-primary:focus,
       a.bg-primary:hover,
       button.bg-primary:focus,
       button.bg-primary:hover {
           background-color: #0062cc!important
       }
       
       .bg-secondary {
           background-color: #6c757d!important
       }
       
       a.bg-secondary:focus,
       a.bg-secondary:hover,
       button.bg-secondary:focus,
       button.bg-secondary:hover {
           background-color: #545b62!important
       }
       
       .bg-success {
           background-color: #28a745!important
       }
       
       a.bg-success:focus,
       a.bg-success:hover,
       button.bg-success:focus,
       button.bg-success:hover {
           background-color: #1e7e34!important
       }
       
       .bg-info {
           background-color: #17a2b8!important
       }
       
       a.bg-info:focus,
       a.bg-info:hover,
       button.bg-info:focus,
       button.bg-info:hover {
           background-color: #117a8b!important
       }
       
       .bg-warning {
           background-color: #ffc107!important
       }
       
       a.bg-warning:focus,
       a.bg-warning:hover,
       button.bg-warning:focus,
       button.bg-warning:hover {
           background-color: #d39e00!important
       }
       
       .bg-danger {
           background-color: #dc3545!important
       }
       
       a.bg-danger:focus,
       a.bg-danger:hover,
       button.bg-danger:focus,
       button.bg-danger:hover {
           background-color: #bd2130!important
       }
       
       .bg-light {
           background-color: #f8f9fa!important
       }
       
       a.bg-light:focus,
       a.bg-light:hover,
       button.bg-light:focus,
       button.bg-light:hover {
           background-color: #dae0e5!important
       }
       
       .bg-dark {
           background-color: #343a40!important
       }
       
       a.bg-dark:focus,
       a.bg-dark:hover,
       button.bg-dark:focus,
       button.bg-dark:hover {
           background-color: #1d2124!important
       }
       
       .bg-white {
           background-color: #fff!important
       }
       
       .bg-transparent {
           background-color: transparent!important
       }
       
       .border {
           border: 1px solid #dee2e6!important
       }
       
       .border-top {
           border-top: 1px solid #dee2e6!important
       }
       
       .border-right {
           border-right: 1px solid #dee2e6!important
       }
       
       .border-bottom {
           border-bottom: 1px solid #dee2e6!important
       }
       
       .border-left {
           border-left: 1px solid #dee2e6!important
       }
       
       .border-0 {
           border: 0!important
       }
       
       .border-top-0 {
           border-top: 0!important
       }
       
       .border-right-0 {
           border-right: 0!important
       }
       
       .border-bottom-0 {
           border-bottom: 0!important
       }
       
       .border-left-0 {
           border-left: 0!important
       }
       
       .border-primary {
           border-color: #007bff!important
       }
       
       .border-secondary {
           border-color: #6c757d!important
       }
       
       .border-success {
           border-color: #28a745!important
       }
       
       .border-info {
           border-color: #17a2b8!important
       }
       
       .border-warning {
           border-color: #ffc107!important
       }
       
       .border-danger {
           border-color: #dc3545!important
       }
       
       .border-light {
           border-color: #f8f9fa!important
       }
       
       .border-dark {
           border-color: #343a40!important
       }
       
       .border-white {
           border-color: #fff!important
       }
       
       .rounded {
           border-radius: .25rem!important
       }
       
       .rounded-top {
           border-top-left-radius: .25rem!important;
           border-top-right-radius: .25rem!important
       }
       
       .rounded-right {
           border-top-right-radius: .25rem!important;
           border-bottom-right-radius: .25rem!important
       }
       
       .rounded-bottom {
           border-bottom-right-radius: .25rem!important;
           border-bottom-left-radius: .25rem!important
       }
       
       .rounded-left {
           border-top-left-radius: .25rem!important;
           border-bottom-left-radius: .25rem!important
       }
       
       .rounded-circle {
           border-radius: 50%!important
       }
       
       .rounded-0 {
           border-radius: 0!important
       }
       
       .clearfix::after {
           display: block;
           clear: both;
           content: ""
       }
       
       .d-none {
           display: none!important
       }
       
       .d-inline {
           display: inline!important
       }
       
       .d-inline-block {
           display: inline-block!important
       }
       
       .d-block {
           display: block!important
       }
       
       .d-table {
           display: table!important
       }
       
       .d-table-row {
           display: table-row!important
       }
       
       .d-table-cell {
           display: table-cell!important
       }
       
       .d-flex {
           display: -webkit-box!important;
           display: -ms-flexbox!important;
           display: flex!important
       }
       
       .d-inline-flex {
           display: -webkit-inline-box!important;
           display: -ms-inline-flexbox!important;
           display: inline-flex!important
       }
       
       @media (min-width:576px) {
           .d-sm-none {
               display: none!important
           }
           .d-sm-inline {
               display: inline!important
           }
           .d-sm-inline-block {
               display: inline-block!important
           }
           .d-sm-block {
               display: block!important
           }
           .d-sm-table {
               display: table!important
           }
           .d-sm-table-row {
               display: table-row!important
           }
           .d-sm-table-cell {
               display: table-cell!important
           }
           .d-sm-flex {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important
           }
           .d-sm-inline-flex {
               display: -webkit-inline-box!important;
               display: -ms-inline-flexbox!important;
               display: inline-flex!important
           }
       }
       
       @media (min-width:768px) {
           .d-md-none {
               display: none!important
           }
           .d-md-inline {
               display: inline!important
           }
           .d-md-inline-block {
               display: inline-block!important
           }
           .d-md-block {
               display: block!important
           }
           .d-md-table {
               display: table!important
           }
           .d-md-table-row {
               display: table-row!important
           }
           .d-md-table-cell {
               display: table-cell!important
           }
           .d-md-flex {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important
           }
           .d-md-inline-flex {
               display: -webkit-inline-box!important;
               display: -ms-inline-flexbox!important;
               display: inline-flex!important
           }
       }
       
       @media (min-width:992px) {
           .d-lg-none {
               display: none!important
           }
           .d-lg-inline {
               display: inline!important
           }
           .d-lg-inline-block {
               display: inline-block!important
           }
           .d-lg-block {
               display: block!important
           }
           .d-lg-table {
               display: table!important
           }
           .d-lg-table-row {
               display: table-row!important
           }
           .d-lg-table-cell {
               display: table-cell!important
           }
           .d-lg-flex {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important
           }
           .d-lg-inline-flex {
               display: -webkit-inline-box!important;
               display: -ms-inline-flexbox!important;
               display: inline-flex!important
           }
       }
       
       @media (min-width:1200px) {
           .d-xl-none {
               display: none!important
           }
           .d-xl-inline {
               display: inline!important
           }
           .d-xl-inline-block {
               display: inline-block!important
           }
           .d-xl-block {
               display: block!important
           }
           .d-xl-table {
               display: table!important
           }
           .d-xl-table-row {
               display: table-row!important
           }
           .d-xl-table-cell {
               display: table-cell!important
           }
           .d-xl-flex {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important
           }
           .d-xl-inline-flex {
               display: -webkit-inline-box!important;
               display: -ms-inline-flexbox!important;
               display: inline-flex!important
           }
       }
       
       @media print {
           .d-print-none {
               display: none!important
           }
           .d-print-inline {
               display: inline!important
           }
           .d-print-inline-block {
               display: inline-block!important
           }
           .d-print-block {
               display: block!important
           }
           .d-print-table {
               display: table!important
           }
           .d-print-table-row {
               display: table-row!important
           }
           .d-print-table-cell {
               display: table-cell!important
           }
           .d-print-flex {
               display: -webkit-box!important;
               display: -ms-flexbox!important;
               display: flex!important
           }
           .d-print-inline-flex {
               display: -webkit-inline-box!important;
               display: -ms-inline-flexbox!important;
               display: inline-flex!important
           }
       }
       
       .embed-responsive {
           position: relative;
           display: block;
           width: 100%;
           padding: 0;
           overflow: hidden
       }
       
       .embed-responsive::before {
           display: block;
           content: ""
       }
       
       .embed-responsive .embed-responsive-item,
       .embed-responsive embed,
       .embed-responsive iframe,
       .embed-responsive object,
       .embed-responsive video {
           position: absolute;
           top: 0;
           bottom: 0;
           left: 0;
           width: 100%;
           height: 100%;
           border: 0
       }
       
       .embed-responsive-21by9::before {
           padding-top: 42.857143%
       }
       
       .embed-responsive-16by9::before {
           padding-top: 56.25%
       }
       
       .embed-responsive-4by3::before {
           padding-top: 75%
       }
       
       .embed-responsive-1by1::before {
           padding-top: 100%
       }
       
       .flex-row {
           -webkit-box-orient: horizontal!important;
           -webkit-box-direction: normal!important;
           -ms-flex-direction: row!important;
           flex-direction: row!important
       }
       
       .flex-column {
           -webkit-box-orient: vertical!important;
           -webkit-box-direction: normal!important;
           -ms-flex-direction: column!important;
           flex-direction: column!important
       }
       
       .flex-row-reverse {
           -webkit-box-orient: horizontal!important;
           -webkit-box-direction: reverse!important;
           -ms-flex-direction: row-reverse!important;
           flex-direction: row-reverse!important
       }
       
       .flex-column-reverse {
           -webkit-box-orient: vertical!important;
           -webkit-box-direction: reverse!important;
           -ms-flex-direction: column-reverse!important;
           flex-direction: column-reverse!important
       }
       
       .flex-wrap {
           -ms-flex-wrap: wrap!important;
           flex-wrap: wrap!important
       }
       
       .flex-nowrap {
           -ms-flex-wrap: nowrap!important;
           flex-wrap: nowrap!important
       }
       
       .flex-wrap-reverse {
           -ms-flex-wrap: wrap-reverse!important;
           flex-wrap: wrap-reverse!important
       }
       
       .justify-content-start {
           -webkit-box-pack: start!important;
           -ms-flex-pack: start!important;
           justify-content: flex-start!important
       }
       
       .justify-content-end {
           -webkit-box-pack: end!important;
           -ms-flex-pack: end!important;
           justify-content: flex-end!important
       }
       
       .justify-content-center {
           -webkit-box-pack: center!important;
           -ms-flex-pack: center!important;
           justify-content: center!important
       }
       
       .justify-content-between {
           -webkit-box-pack: justify!important;
           -ms-flex-pack: justify!important;
           justify-content: space-between!important
       }
       
       .justify-content-around {
           -ms-flex-pack: distribute!important;
           justify-content: space-around!important
       }
       
       .align-items-start {
           -webkit-box-align: start!important;
           -ms-flex-align: start!important;
           align-items: flex-start!important
       }
       
       .align-items-end {
           -webkit-box-align: end!important;
           -ms-flex-align: end!important;
           align-items: flex-end!important
       }
       
       .align-items-center {
           -webkit-box-align: center!important;
           -ms-flex-align: center!important;
           align-items: center!important
       }
       
       .align-items-baseline {
           -webkit-box-align: baseline!important;
           -ms-flex-align: baseline!important;
           align-items: baseline!important
       }
       
       .align-items-stretch {
           -webkit-box-align: stretch!important;
           -ms-flex-align: stretch!important;
           align-items: stretch!important
       }
       
       .align-content-start {
           -ms-flex-line-pack: start!important;
           align-content: flex-start!important
       }
       
       .align-content-end {
           -ms-flex-line-pack: end!important;
           align-content: flex-end!important
       }
       
       .align-content-center {
           -ms-flex-line-pack: center!important;
           align-content: center!important
       }
       
       .align-content-between {
           -ms-flex-line-pack: justify!important;
           align-content: space-between!important
       }
       
       .align-content-around {
           -ms-flex-line-pack: distribute!important;
           align-content: space-around!important
       }
       
       .align-content-stretch {
           -ms-flex-line-pack: stretch!important;
           align-content: stretch!important
       }
       
       .align-self-auto {
           -ms-flex-item-align: auto!important;
           align-self: auto!important
       }
       
       .align-self-start {
           -ms-flex-item-align: start!important;
           align-self: flex-start!important
       }
       
       .align-self-end {
           -ms-flex-item-align: end!important;
           align-self: flex-end!important
       }
       
       .align-self-center {
           -ms-flex-item-align: center!important;
           align-self: center!important
       }
       
       .align-self-baseline {
           -ms-flex-item-align: baseline!important;
           align-self: baseline!important
       }
       
       .align-self-stretch {
           -ms-flex-item-align: stretch!important;
           align-self: stretch!important
       }
       
       @media (min-width:576px) {
           .flex-sm-row {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: row!important;
               flex-direction: row!important
           }
           .flex-sm-column {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: column!important;
               flex-direction: column!important
           }
           .flex-sm-row-reverse {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: row-reverse!important;
               flex-direction: row-reverse!important
           }
           .flex-sm-column-reverse {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: column-reverse!important;
               flex-direction: column-reverse!important
           }
           .flex-sm-wrap {
               -ms-flex-wrap: wrap!important;
               flex-wrap: wrap!important
           }
           .flex-sm-nowrap {
               -ms-flex-wrap: nowrap!important;
               flex-wrap: nowrap!important
           }
           .flex-sm-wrap-reverse {
               -ms-flex-wrap: wrap-reverse!important;
               flex-wrap: wrap-reverse!important
           }
           .justify-content-sm-start {
               -webkit-box-pack: start!important;
               -ms-flex-pack: start!important;
               justify-content: flex-start!important
           }
           .justify-content-sm-end {
               -webkit-box-pack: end!important;
               -ms-flex-pack: end!important;
               justify-content: flex-end!important
           }
           .justify-content-sm-center {
               -webkit-box-pack: center!important;
               -ms-flex-pack: center!important;
               justify-content: center!important
           }
           .justify-content-sm-between {
               -webkit-box-pack: justify!important;
               -ms-flex-pack: justify!important;
               justify-content: space-between!important
           }
           .justify-content-sm-around {
               -ms-flex-pack: distribute!important;
               justify-content: space-around!important
           }
           .align-items-sm-start {
               -webkit-box-align: start!important;
               -ms-flex-align: start!important;
               align-items: flex-start!important
           }
           .align-items-sm-end {
               -webkit-box-align: end!important;
               -ms-flex-align: end!important;
               align-items: flex-end!important
           }
           .align-items-sm-center {
               -webkit-box-align: center!important;
               -ms-flex-align: center!important;
               align-items: center!important
           }
           .align-items-sm-baseline {
               -webkit-box-align: baseline!important;
               -ms-flex-align: baseline!important;
               align-items: baseline!important
           }
           .align-items-sm-stretch {
               -webkit-box-align: stretch!important;
               -ms-flex-align: stretch!important;
               align-items: stretch!important
           }
           .align-content-sm-start {
               -ms-flex-line-pack: start!important;
               align-content: flex-start!important
           }
           .align-content-sm-end {
               -ms-flex-line-pack: end!important;
               align-content: flex-end!important
           }
           .align-content-sm-center {
               -ms-flex-line-pack: center!important;
               align-content: center!important
           }
           .align-content-sm-between {
               -ms-flex-line-pack: justify!important;
               align-content: space-between!important
           }
           .align-content-sm-around {
               -ms-flex-line-pack: distribute!important;
               align-content: space-around!important
           }
           .align-content-sm-stretch {
               -ms-flex-line-pack: stretch!important;
               align-content: stretch!important
           }
           .align-self-sm-auto {
               -ms-flex-item-align: auto!important;
               align-self: auto!important
           }
           .align-self-sm-start {
               -ms-flex-item-align: start!important;
               align-self: flex-start!important
           }
           .align-self-sm-end {
               -ms-flex-item-align: end!important;
               align-self: flex-end!important
           }
           .align-self-sm-center {
               -ms-flex-item-align: center!important;
               align-self: center!important
           }
           .align-self-sm-baseline {
               -ms-flex-item-align: baseline!important;
               align-self: baseline!important
           }
           .align-self-sm-stretch {
               -ms-flex-item-align: stretch!important;
               align-self: stretch!important
           }
       }
       
       @media (min-width:768px) {
           .flex-md-row {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: row!important;
               flex-direction: row!important
           }
           .flex-md-column {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: column!important;
               flex-direction: column!important
           }
           .flex-md-row-reverse {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: row-reverse!important;
               flex-direction: row-reverse!important
           }
           .flex-md-column-reverse {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: column-reverse!important;
               flex-direction: column-reverse!important
           }
           .flex-md-wrap {
               -ms-flex-wrap: wrap!important;
               flex-wrap: wrap!important
           }
           .flex-md-nowrap {
               -ms-flex-wrap: nowrap!important;
               flex-wrap: nowrap!important
           }
           .flex-md-wrap-reverse {
               -ms-flex-wrap: wrap-reverse!important;
               flex-wrap: wrap-reverse!important
           }
           .justify-content-md-start {
               -webkit-box-pack: start!important;
               -ms-flex-pack: start!important;
               justify-content: flex-start!important
           }
           .justify-content-md-end {
               -webkit-box-pack: end!important;
               -ms-flex-pack: end!important;
               justify-content: flex-end!important
           }
           .justify-content-md-center {
               -webkit-box-pack: center!important;
               -ms-flex-pack: center!important;
               justify-content: center!important
           }
           .justify-content-md-between {
               -webkit-box-pack: justify!important;
               -ms-flex-pack: justify!important;
               justify-content: space-between!important
           }
           .justify-content-md-around {
               -ms-flex-pack: distribute!important;
               justify-content: space-around!important
           }
           .align-items-md-start {
               -webkit-box-align: start!important;
               -ms-flex-align: start!important;
               align-items: flex-start!important
           }
           .align-items-md-end {
               -webkit-box-align: end!important;
               -ms-flex-align: end!important;
               align-items: flex-end!important
           }
           .align-items-md-center {
               -webkit-box-align: center!important;
               -ms-flex-align: center!important;
               align-items: center!important
           }
           .align-items-md-baseline {
               -webkit-box-align: baseline!important;
               -ms-flex-align: baseline!important;
               align-items: baseline!important
           }
           .align-items-md-stretch {
               -webkit-box-align: stretch!important;
               -ms-flex-align: stretch!important;
               align-items: stretch!important
           }
           .align-content-md-start {
               -ms-flex-line-pack: start!important;
               align-content: flex-start!important
           }
           .align-content-md-end {
               -ms-flex-line-pack: end!important;
               align-content: flex-end!important
           }
           .align-content-md-center {
               -ms-flex-line-pack: center!important;
               align-content: center!important
           }
           .align-content-md-between {
               -ms-flex-line-pack: justify!important;
               align-content: space-between!important
           }
           .align-content-md-around {
               -ms-flex-line-pack: distribute!important;
               align-content: space-around!important
           }
           .align-content-md-stretch {
               -ms-flex-line-pack: stretch!important;
               align-content: stretch!important
           }
           .align-self-md-auto {
               -ms-flex-item-align: auto!important;
               align-self: auto!important
           }
           .align-self-md-start {
               -ms-flex-item-align: start!important;
               align-self: flex-start!important
           }
           .align-self-md-end {
               -ms-flex-item-align: end!important;
               align-self: flex-end!important
           }
           .align-self-md-center {
               -ms-flex-item-align: center!important;
               align-self: center!important
           }
           .align-self-md-baseline {
               -ms-flex-item-align: baseline!important;
               align-self: baseline!important
           }
           .align-self-md-stretch {
               -ms-flex-item-align: stretch!important;
               align-self: stretch!important
           }
       }
       
       @media (min-width:992px) {
           .flex-lg-row {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: row!important;
               flex-direction: row!important
           }
           .flex-lg-column {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: column!important;
               flex-direction: column!important
           }
           .flex-lg-row-reverse {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: row-reverse!important;
               flex-direction: row-reverse!important
           }
           .flex-lg-column-reverse {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: column-reverse!important;
               flex-direction: column-reverse!important
           }
           .flex-lg-wrap {
               -ms-flex-wrap: wrap!important;
               flex-wrap: wrap!important
           }
           .flex-lg-nowrap {
               -ms-flex-wrap: nowrap!important;
               flex-wrap: nowrap!important
           }
           .flex-lg-wrap-reverse {
               -ms-flex-wrap: wrap-reverse!important;
               flex-wrap: wrap-reverse!important
           }
           .justify-content-lg-start {
               -webkit-box-pack: start!important;
               -ms-flex-pack: start!important;
               justify-content: flex-start!important
           }
           .justify-content-lg-end {
               -webkit-box-pack: end!important;
               -ms-flex-pack: end!important;
               justify-content: flex-end!important
           }
           .justify-content-lg-center {
               -webkit-box-pack: center!important;
               -ms-flex-pack: center!important;
               justify-content: center!important
           }
           .justify-content-lg-between {
               -webkit-box-pack: justify!important;
               -ms-flex-pack: justify!important;
               justify-content: space-between!important
           }
           .justify-content-lg-around {
               -ms-flex-pack: distribute!important;
               justify-content: space-around!important
           }
           .align-items-lg-start {
               -webkit-box-align: start!important;
               -ms-flex-align: start!important;
               align-items: flex-start!important
           }
           .align-items-lg-end {
               -webkit-box-align: end!important;
               -ms-flex-align: end!important;
               align-items: flex-end!important
           }
           .align-items-lg-center {
               -webkit-box-align: center!important;
               -ms-flex-align: center!important;
               align-items: center!important
           }
           .align-items-lg-baseline {
               -webkit-box-align: baseline!important;
               -ms-flex-align: baseline!important;
               align-items: baseline!important
           }
           .align-items-lg-stretch {
               -webkit-box-align: stretch!important;
               -ms-flex-align: stretch!important;
               align-items: stretch!important
           }
           .align-content-lg-start {
               -ms-flex-line-pack: start!important;
               align-content: flex-start!important
           }
           .align-content-lg-end {
               -ms-flex-line-pack: end!important;
               align-content: flex-end!important
           }
           .align-content-lg-center {
               -ms-flex-line-pack: center!important;
               align-content: center!important
           }
           .align-content-lg-between {
               -ms-flex-line-pack: justify!important;
               align-content: space-between!important
           }
           .align-content-lg-around {
               -ms-flex-line-pack: distribute!important;
               align-content: space-around!important
           }
           .align-content-lg-stretch {
               -ms-flex-line-pack: stretch!important;
               align-content: stretch!important
           }
           .align-self-lg-auto {
               -ms-flex-item-align: auto!important;
               align-self: auto!important
           }
           .align-self-lg-start {
               -ms-flex-item-align: start!important;
               align-self: flex-start!important
           }
           .align-self-lg-end {
               -ms-flex-item-align: end!important;
               align-self: flex-end!important
           }
           .align-self-lg-center {
               -ms-flex-item-align: center!important;
               align-self: center!important
           }
           .align-self-lg-baseline {
               -ms-flex-item-align: baseline!important;
               align-self: baseline!important
           }
           .align-self-lg-stretch {
               -ms-flex-item-align: stretch!important;
               align-self: stretch!important
           }
       }
       
       @media (min-width:1200px) {
           .flex-xl-row {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: row!important;
               flex-direction: row!important
           }
           .flex-xl-column {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: normal!important;
               -ms-flex-direction: column!important;
               flex-direction: column!important
           }
           .flex-xl-row-reverse {
               -webkit-box-orient: horizontal!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: row-reverse!important;
               flex-direction: row-reverse!important
           }
           .flex-xl-column-reverse {
               -webkit-box-orient: vertical!important;
               -webkit-box-direction: reverse!important;
               -ms-flex-direction: column-reverse!important;
               flex-direction: column-reverse!important
           }
           .flex-xl-wrap {
               -ms-flex-wrap: wrap!important;
               flex-wrap: wrap!important
           }
           .flex-xl-nowrap {
               -ms-flex-wrap: nowrap!important;
               flex-wrap: nowrap!important
           }
           .flex-xl-wrap-reverse {
               -ms-flex-wrap: wrap-reverse!important;
               flex-wrap: wrap-reverse!important
           }
           .justify-content-xl-start {
               -webkit-box-pack: start!important;
               -ms-flex-pack: start!important;
               justify-content: flex-start!important
           }
           .justify-content-xl-end {
               -webkit-box-pack: end!important;
               -ms-flex-pack: end!important;
               justify-content: flex-end!important
           }
           .justify-content-xl-center {
               -webkit-box-pack: center!important;
               -ms-flex-pack: center!important;
               justify-content: center!important
           }
           .justify-content-xl-between {
               -webkit-box-pack: justify!important;
               -ms-flex-pack: justify!important;
               justify-content: space-between!important
           }
           .justify-content-xl-around {
               -ms-flex-pack: distribute!important;
               justify-content: space-around!important
           }
           .align-items-xl-start {
               -webkit-box-align: start!important;
               -ms-flex-align: start!important;
               align-items: flex-start!important
           }
           .align-items-xl-end {
               -webkit-box-align: end!important;
               -ms-flex-align: end!important;
               align-items: flex-end!important
           }
           .align-items-xl-center {
               -webkit-box-align: center!important;
               -ms-flex-align: center!important;
               align-items: center!important
           }
           .align-items-xl-baseline {
               -webkit-box-align: baseline!important;
               -ms-flex-align: baseline!important;
               align-items: baseline!important
           }
           .align-items-xl-stretch {
               -webkit-box-align: stretch!important;
               -ms-flex-align: stretch!important;
               align-items: stretch!important
           }
           .align-content-xl-start {
               -ms-flex-line-pack: start!important;
               align-content: flex-start!important
           }
           .align-content-xl-end {
               -ms-flex-line-pack: end!important;
               align-content: flex-end!important
           }
           .align-content-xl-center {
               -ms-flex-line-pack: center!important;
               align-content: center!important
           }
           .align-content-xl-between {
               -ms-flex-line-pack: justify!important;
               align-content: space-between!important
           }
           .align-content-xl-around {
               -ms-flex-line-pack: distribute!important;
               align-content: space-around!important
           }
           .align-content-xl-stretch {
               -ms-flex-line-pack: stretch!important;
               align-content: stretch!important
           }
           .align-self-xl-auto {
               -ms-flex-item-align: auto!important;
               align-self: auto!important
           }
           .align-self-xl-start {
               -ms-flex-item-align: start!important;
               align-self: flex-start!important
           }
           .align-self-xl-end {
               -ms-flex-item-align: end!important;
               align-self: flex-end!important
           }
           .align-self-xl-center {
               -ms-flex-item-align: center!important;
               align-self: center!important
           }
           .align-self-xl-baseline {
               -ms-flex-item-align: baseline!important;
               align-self: baseline!important
           }
           .align-self-xl-stretch {
               -ms-flex-item-align: stretch!important;
               align-self: stretch!important
           }
       }
       
       .float-left {
           float: left!important
       }
       
       .float-right {
           float: right!important
       }
       
       .float-none {
           float: none!important
       }
       
       @media (min-width:576px) {
           .float-sm-left {
               float: left!important
           }
           .float-sm-right {
               float: right!important
           }
           .float-sm-none {
               float: none!important
           }
       }
       
       @media (min-width:768px) {
           .float-md-left {
               float: left!important
           }
           .float-md-right {
               float: right!important
           }
           .float-md-none {
               float: none!important
           }
       }
       
       @media (min-width:992px) {
           .float-lg-left {
               float: left!important
           }
           .float-lg-right {
               float: right!important
           }
           .float-lg-none {
               float: none!important
           }
       }
       
       @media (min-width:1200px) {
           .float-xl-left {
               float: left!important
           }
           .float-xl-right {
               float: right!important
           }
           .float-xl-none {
               float: none!important
           }
       }
       
       .position-static {
           position: static!important
       }
       
       .position-relative {
           position: relative!important
       }
       
       .position-absolute {
           position: absolute!important
       }
       
       .position-fixed {
           position: fixed!important
       }
       
       .position-sticky {
           position: -webkit-sticky!important;
           position: sticky!important
       }
       
       .fixed-top {
           position: fixed;
           top: 0;
           right: 0;
           left: 0;
           z-index: 1030
       }
       
       .fixed-bottom {
           position: fixed;
           right: 0;
           bottom: 0;
           left: 0;
           z-index: 1030
       }
       
       @supports ((position:-webkit-sticky) or (position:sticky)) {
           .sticky-top {
               position: -webkit-sticky;
               position: sticky;
               top: 0;
               z-index: 1020
           }
       }
       
       .sr-only {
           position: absolute;
           width: 1px;
           height: 1px;
           padding: 0;
           overflow: hidden;
           clip: rect(0, 0, 0, 0);
           white-space: nowrap;
           -webkit-clip-path: inset(50%);
           clip-path: inset(50%);
           border: 0
       }
       
       .sr-only-focusable:active,
       .sr-only-focusable:focus {
           position: static;
           width: auto;
           height: auto;
           overflow: visible;
           clip: auto;
           white-space: normal;
           -webkit-clip-path: none;
           clip-path: none
       }
       
       .w-25 {
           width: 25%!important
       }
       
       .w-50 {
           width: 50%!important
       }
       
       .w-75 {
           width: 75%!important
       }
       
       .w-100 {
           width: 100%!important
       }
       
       .h-25 {
           height: 25%!important
       }
       
       .h-50 {
           height: 50%!important
       }
       
       .h-75 {
           height: 75%!important
       }
       
       .h-100 {
           height: 100%!important
       }
       
       .mw-100 {
           max-width: 100%!important
       }
       
       .mh-100 {
           max-height: 100%!important
       }
       
       .m-0 {
           margin: 0!important
       }
       
       .mt-0,
       .my-0 {
           margin-top: 0!important
       }
       
       .mr-0,
       .mx-0 {
           margin-right: 0!important
       }
       
       .mb-0,
       .my-0 {
           margin-bottom: 0!important
       }
       
       .ml-0,
       .mx-0 {
           margin-left: 0!important
       }
       
       .m-1 {
           margin: .25rem!important
       }
       
       .mt-1,
       .my-1 {
           margin-top: .25rem!important
       }
       
       .mr-1,
       .mx-1 {
           margin-right: .25rem!important
       }
       
       .mb-1,
       .my-1 {
           margin-bottom: .25rem!important
       }
       
       .ml-1,
       .mx-1 {
           margin-left: .25rem!important
       }
       
       .m-2 {
           margin: .5rem!important
       }
       
       .mt-2,
       .my-2 {
           margin-top: .5rem!important
       }
       
       .mr-2,
       .mx-2 {
           margin-right: .5rem!important
       }
       
       .mb-2,
       .my-2 {
           margin-bottom: .5rem!important
       }
       
       .ml-2,
       .mx-2 {
           margin-left: .5rem!important
       }
       
       .m-3 {
           margin: 1rem!important
       }
       
       .mt-3,
       .my-3 {
           margin-top: 1rem!important
       }
       
       .mr-3,
       .mx-3 {
           margin-right: 1rem!important
       }
       
       .mb-3,
       .my-3 {
           margin-bottom: 1rem!important
       }
       
       .ml-3,
       .mx-3 {
           margin-left: 1rem!important
       }
       
       .m-4 {
           margin: 1.5rem!important
       }
       
       .mt-4,
       .my-4 {
           margin-top: 1.5rem!important
       }
       
       .mr-4,
       .mx-4 {
           margin-right: 1.5rem!important
       }
       
       .mb-4,
       .my-4 {
           margin-bottom: 1.5rem!important
       }
       
       .ml-4,
       .mx-4 {
           margin-left: 1.5rem!important
       }
       
       .m-5 {
           margin: 3rem!important
       }
       
       .mt-5,
       .my-5 {
           margin-top: 3rem!important
       }
       
       .mr-5,
       .mx-5 {
           margin-right: 3rem!important
       }
       
       .mb-5,
       .my-5 {
           margin-bottom: 3rem!important
       }
       
       .ml-5,
       .mx-5 {
           margin-left: 3rem!important
       }
       
       .p-0 {
           padding: 0!important
       }
       
       .pt-0,
       .py-0 {
           padding-top: 0!important
       }
       
       .pr-0,
       .px-0 {
           padding-right: 0!important
       }
       
       .pb-0,
       .py-0 {
           padding-bottom: 0!important
       }
       
       .pl-0,
       .px-0 {
           padding-left: 0!important
       }
       
       .p-1 {
           padding: .25rem!important
       }
       
       .pt-1,
       .py-1 {
           padding-top: .25rem!important
       }
       
       .pr-1,
       .px-1 {
           padding-right: .25rem!important
       }
       
       .pb-1,
       .py-1 {
           padding-bottom: .25rem!important
       }
       
       .pl-1,
       .px-1 {
           padding-left: .25rem!important
       }
       
       .p-2 {
           padding: .5rem!important
       }
       
       .pt-2,
       .py-2 {
           padding-top: .5rem!important
       }
       
       .pr-2,
       .px-2 {
           padding-right: .5rem!important
       }
       
       .pb-2,
       .py-2 {
           padding-bottom: .5rem!important
       }
       
       .pl-2,
       .px-2 {
           padding-left: .5rem!important
       }
       
       .p-3 {
           padding: 1rem!important
       }
       
       .pt-3,
       .py-3 {
           padding-top: 1rem!important
       }
       
       .pr-3,
       .px-3 {
           padding-right: 1rem!important
       }
       
       .pb-3,
       .py-3 {
           padding-bottom: 1rem!important
       }
       
       .pl-3,
       .px-3 {
           padding-left: 1rem!important
       }
       
       .p-4 {
           padding: 1.5rem!important
       }
       
       .pt-4,
       .py-4 {
           padding-top: 1.5rem!important
       }
       
       .pr-4,
       .px-4 {
           padding-right: 1.5rem!important
       }
       
       .pb-4,
       .py-4 {
           padding-bottom: 1.5rem!important
       }
       
       .pl-4,
       .px-4 {
           padding-left: 1.5rem!important
       }
       
       .p-5 {
           padding: 3rem!important
       }
       
       .pt-5,
       .py-5 {
           padding-top: 3rem!important
       }
       
       .pr-5,
       .px-5 {
           padding-right: 3rem!important
       }
       
       .pb-5,
       .py-5 {
           padding-bottom: 3rem!important
       }
       
       .pl-5,
       .px-5 {
           padding-left: 3rem!important
       }
       
       .m-auto {
           margin: auto!important
       }
       
       .mt-auto,
       .my-auto {
           margin-top: auto!important
       }
       
       .mr-auto,
       .mx-auto {
           margin-right: auto!important
       }
       
       .mb-auto,
       .my-auto {
           margin-bottom: auto!important
       }
       
       .ml-auto,
       .mx-auto {
           margin-left: auto!important
       }
       
       @media (min-width:576px) {
           .m-sm-0 {
               margin: 0!important
           }
           .mt-sm-0,
           .my-sm-0 {
               margin-top: 0!important
           }
           .mr-sm-0,
           .mx-sm-0 {
               margin-right: 0!important
           }
           .mb-sm-0,
           .my-sm-0 {
               margin-bottom: 0!important
           }
           .ml-sm-0,
           .mx-sm-0 {
               margin-left: 0!important
           }
           .m-sm-1 {
               margin: .25rem!important
           }
           .mt-sm-1,
           .my-sm-1 {
               margin-top: .25rem!important
           }
           .mr-sm-1,
           .mx-sm-1 {
               margin-right: .25rem!important
           }
           .mb-sm-1,
           .my-sm-1 {
               margin-bottom: .25rem!important
           }
           .ml-sm-1,
           .mx-sm-1 {
               margin-left: .25rem!important
           }
           .m-sm-2 {
               margin: .5rem!important
           }
           .mt-sm-2,
           .my-sm-2 {
               margin-top: .5rem!important
           }
           .mr-sm-2,
           .mx-sm-2 {
               margin-right: .5rem!important
           }
           .mb-sm-2,
           .my-sm-2 {
               margin-bottom: .5rem!important
           }
           .ml-sm-2,
           .mx-sm-2 {
               margin-left: .5rem!important
           }
           .m-sm-3 {
               margin: 1rem!important
           }
           .mt-sm-3,
           .my-sm-3 {
               margin-top: 1rem!important
           }
           .mr-sm-3,
           .mx-sm-3 {
               margin-right: 1rem!important
           }
           .mb-sm-3,
           .my-sm-3 {
               margin-bottom: 1rem!important
           }
           .ml-sm-3,
           .mx-sm-3 {
               margin-left: 1rem!important
           }
           .m-sm-4 {
               margin: 1.5rem!important
           }
           .mt-sm-4,
           .my-sm-4 {
               margin-top: 1.5rem!important
           }
           .mr-sm-4,
           .mx-sm-4 {
               margin-right: 1.5rem!important
           }
           .mb-sm-4,
           .my-sm-4 {
               margin-bottom: 1.5rem!important
           }
           .ml-sm-4,
           .mx-sm-4 {
               margin-left: 1.5rem!important
           }
           .m-sm-5 {
               margin: 3rem!important
           }
           .mt-sm-5,
           .my-sm-5 {
               margin-top: 3rem!important
           }
           .mr-sm-5,
           .mx-sm-5 {
               margin-right: 3rem!important
           }
           .mb-sm-5,
           .my-sm-5 {
               margin-bottom: 3rem!important
           }
           .ml-sm-5,
           .mx-sm-5 {
               margin-left: 3rem!important
           }
           .p-sm-0 {
               padding: 0!important
           }
           .pt-sm-0,
           .py-sm-0 {
               padding-top: 0!important
           }
           .pr-sm-0,
           .px-sm-0 {
               padding-right: 0!important
           }
           .pb-sm-0,
           .py-sm-0 {
               padding-bottom: 0!important
           }
           .pl-sm-0,
           .px-sm-0 {
               padding-left: 0!important
           }
           .p-sm-1 {
               padding: .25rem!important
           }
           .pt-sm-1,
           .py-sm-1 {
               padding-top: .25rem!important
           }
           .pr-sm-1,
           .px-sm-1 {
               padding-right: .25rem!important
           }
           .pb-sm-1,
           .py-sm-1 {
               padding-bottom: .25rem!important
           }
           .pl-sm-1,
           .px-sm-1 {
               padding-left: .25rem!important
           }
           .p-sm-2 {
               padding: .5rem!important
           }
           .pt-sm-2,
           .py-sm-2 {
               padding-top: .5rem!important
           }
           .pr-sm-2,
           .px-sm-2 {
               padding-right: .5rem!important
           }
           .pb-sm-2,
           .py-sm-2 {
               padding-bottom: .5rem!important
           }
           .pl-sm-2,
           .px-sm-2 {
               padding-left: .5rem!important
           }
           .p-sm-3 {
               padding: 1rem!important
           }
           .pt-sm-3,
           .py-sm-3 {
               padding-top: 1rem!important
           }
           .pr-sm-3,
           .px-sm-3 {
               padding-right: 1rem!important
           }
           .pb-sm-3,
           .py-sm-3 {
               padding-bottom: 1rem!important
           }
           .pl-sm-3,
           .px-sm-3 {
               padding-left: 1rem!important
           }
           .p-sm-4 {
               padding: 1.5rem!important
           }
           .pt-sm-4,
           .py-sm-4 {
               padding-top: 1.5rem!important
           }
           .pr-sm-4,
           .px-sm-4 {
               padding-right: 1.5rem!important
           }
           .pb-sm-4,
           .py-sm-4 {
               padding-bottom: 1.5rem!important
           }
           .pl-sm-4,
           .px-sm-4 {
               padding-left: 1.5rem!important
           }
           .p-sm-5 {
               padding: 3rem!important
           }
           .pt-sm-5,
           .py-sm-5 {
               padding-top: 3rem!important
           }
           .pr-sm-5,
           .px-sm-5 {
               padding-right: 3rem!important
           }
           .pb-sm-5,
           .py-sm-5 {
               padding-bottom: 3rem!important
           }
           .pl-sm-5,
           .px-sm-5 {
               padding-left: 3rem!important
           }
           .m-sm-auto {
               margin: auto!important
           }
           .mt-sm-auto,
           .my-sm-auto {
               margin-top: auto!important
           }
           .mr-sm-auto,
           .mx-sm-auto {
               margin-right: auto!important
           }
           .mb-sm-auto,
           .my-sm-auto {
               margin-bottom: auto!important
           }
           .ml-sm-auto,
           .mx-sm-auto {
               margin-left: auto!important
           }
       }
       
       @media (min-width:768px) {
           .m-md-0 {
               margin: 0!important
           }
           .mt-md-0,
           .my-md-0 {
               margin-top: 0!important
           }
           .mr-md-0,
           .mx-md-0 {
               margin-right: 0!important
           }
           .mb-md-0,
           .my-md-0 {
               margin-bottom: 0!important
           }
           .ml-md-0,
           .mx-md-0 {
               margin-left: 0!important
           }
           .m-md-1 {
               margin: .25rem!important
           }
           .mt-md-1,
           .my-md-1 {
               margin-top: .25rem!important
           }
           .mr-md-1,
           .mx-md-1 {
               margin-right: .25rem!important
           }
           .mb-md-1,
           .my-md-1 {
               margin-bottom: .25rem!important
           }
           .ml-md-1,
           .mx-md-1 {
               margin-left: .25rem!important
           }
           .m-md-2 {
               margin: .5rem!important
           }
           .mt-md-2,
           .my-md-2 {
               margin-top: .5rem!important
           }
           .mr-md-2,
           .mx-md-2 {
               margin-right: .5rem!important
           }
           .mb-md-2,
           .my-md-2 {
               margin-bottom: .5rem!important
           }
           .ml-md-2,
           .mx-md-2 {
               margin-left: .5rem!important
           }
           .m-md-3 {
               margin: 1rem!important
           }
           .mt-md-3,
           .my-md-3 {
               margin-top: 1rem!important
           }
           .mr-md-3,
           .mx-md-3 {
               margin-right: 1rem!important
           }
           .mb-md-3,
           .my-md-3 {
               margin-bottom: 1rem!important
           }
           .ml-md-3,
           .mx-md-3 {
               margin-left: 1rem!important
           }
           .m-md-4 {
               margin: 1.5rem!important
           }
           .mt-md-4,
           .my-md-4 {
               margin-top: 1.5rem!important
           }
           .mr-md-4,
           .mx-md-4 {
               margin-right: 1.5rem!important
           }
           .mb-md-4,
           .my-md-4 {
               margin-bottom: 1.5rem!important
           }
           .ml-md-4,
           .mx-md-4 {
               margin-left: 1.5rem!important
           }
           .m-md-5 {
               margin: 3rem!important
           }
           .mt-md-5,
           .my-md-5 {
               margin-top: 3rem!important
           }
           .mr-md-5,
           .mx-md-5 {
               margin-right: 3rem!important
           }
           .mb-md-5,
           .my-md-5 {
               margin-bottom: 3rem!important
           }
           .ml-md-5,
           .mx-md-5 {
               margin-left: 3rem!important
           }
           .p-md-0 {
               padding: 0!important
           }
           .pt-md-0,
           .py-md-0 {
               padding-top: 0!important
           }
           .pr-md-0,
           .px-md-0 {
               padding-right: 0!important
           }
           .pb-md-0,
           .py-md-0 {
               padding-bottom: 0!important
           }
           .pl-md-0,
           .px-md-0 {
               padding-left: 0!important
           }
           .p-md-1 {
               padding: .25rem!important
           }
           .pt-md-1,
           .py-md-1 {
               padding-top: .25rem!important
           }
           .pr-md-1,
           .px-md-1 {
               padding-right: .25rem!important
           }
           .pb-md-1,
           .py-md-1 {
               padding-bottom: .25rem!important
           }
           .pl-md-1,
           .px-md-1 {
               padding-left: .25rem!important
           }
           .p-md-2 {
               padding: .5rem!important
           }
           .pt-md-2,
           .py-md-2 {
               padding-top: .5rem!important
           }
           .pr-md-2,
           .px-md-2 {
               padding-right: .5rem!important
           }
           .pb-md-2,
           .py-md-2 {
               padding-bottom: .5rem!important
           }
           .pl-md-2,
           .px-md-2 {
               padding-left: .5rem!important
           }
           .p-md-3 {
               padding: 1rem!important
           }
           .pt-md-3,
           .py-md-3 {
               padding-top: 1rem!important
           }
           .pr-md-3,
           .px-md-3 {
               padding-right: 1rem!important
           }
           .pb-md-3,
           .py-md-3 {
               padding-bottom: 1rem!important
           }
           .pl-md-3,
           .px-md-3 {
               padding-left: 1rem!important
           }
           .p-md-4 {
               padding: 1.5rem!important
           }
           .pt-md-4,
           .py-md-4 {
               padding-top: 1.5rem!important
           }
           .pr-md-4,
           .px-md-4 {
               padding-right: 1.5rem!important
           }
           .pb-md-4,
           .py-md-4 {
               padding-bottom: 1.5rem!important
           }
           .pl-md-4,
           .px-md-4 {
               padding-left: 1.5rem!important
           }
           .p-md-5 {
               padding: 3rem!important
           }
           .pt-md-5,
           .py-md-5 {
               padding-top: 3rem!important
           }
           .pr-md-5,
           .px-md-5 {
               padding-right: 3rem!important
           }
           .pb-md-5,
           .py-md-5 {
               padding-bottom: 3rem!important
           }
           .pl-md-5,
           .px-md-5 {
               padding-left: 3rem!important
           }
           .m-md-auto {
               margin: auto!important
           }
           .mt-md-auto,
           .my-md-auto {
               margin-top: auto!important
           }
           .mr-md-auto,
           .mx-md-auto {
               margin-right: auto!important
           }
           .mb-md-auto,
           .my-md-auto {
               margin-bottom: auto!important
           }
           .ml-md-auto,
           .mx-md-auto {
               margin-left: auto!important
           }
       }
       
       @media (min-width:992px) {
           .m-lg-0 {
               margin: 0!important
           }
           .mt-lg-0,
           .my-lg-0 {
               margin-top: 0!important
           }
           .mr-lg-0,
           .mx-lg-0 {
               margin-right: 0!important
           }
           .mb-lg-0,
           .my-lg-0 {
               margin-bottom: 0!important
           }
           .ml-lg-0,
           .mx-lg-0 {
               margin-left: 0!important
           }
           .m-lg-1 {
               margin: .25rem!important
           }
           .mt-lg-1,
           .my-lg-1 {
               margin-top: .25rem!important
           }
           .mr-lg-1,
           .mx-lg-1 {
               margin-right: .25rem!important
           }
           .mb-lg-1,
           .my-lg-1 {
               margin-bottom: .25rem!important
           }
           .ml-lg-1,
           .mx-lg-1 {
               margin-left: .25rem!important
           }
           .m-lg-2 {
               margin: .5rem!important
           }
           .mt-lg-2,
           .my-lg-2 {
               margin-top: .5rem!important
           }
           .mr-lg-2,
           .mx-lg-2 {
               margin-right: .5rem!important
           }
           .mb-lg-2,
           .my-lg-2 {
               margin-bottom: .5rem!important
           }
           .ml-lg-2,
           .mx-lg-2 {
               margin-left: .5rem!important
           }
           .m-lg-3 {
               margin: 1rem!important
           }
           .mt-lg-3,
           .my-lg-3 {
               margin-top: 1rem!important
           }
           .mr-lg-3,
           .mx-lg-3 {
               margin-right: 1rem!important
           }
           .mb-lg-3,
           .my-lg-3 {
               margin-bottom: 1rem!important
           }
           .ml-lg-3,
           .mx-lg-3 {
               margin-left: 1rem!important
           }
           .m-lg-4 {
               margin: 1.5rem!important
           }
           .mt-lg-4,
           .my-lg-4 {
               margin-top: 1.5rem!important
           }
           .mr-lg-4,
           .mx-lg-4 {
               margin-right: 1.5rem!important
           }
           .mb-lg-4,
           .my-lg-4 {
               margin-bottom: 1.5rem!important
           }
           .ml-lg-4,
           .mx-lg-4 {
               margin-left: 1.5rem!important
           }
           .m-lg-5 {
               margin: 3rem!important
           }
           .mt-lg-5,
           .my-lg-5 {
               margin-top: 3rem!important
           }
           .mr-lg-5,
           .mx-lg-5 {
               margin-right: 3rem!important
           }
           .mb-lg-5,
           .my-lg-5 {
               margin-bottom: 3rem!important
           }
           .ml-lg-5,
           .mx-lg-5 {
               margin-left: 3rem!important
           }
           .p-lg-0 {
               padding: 0!important
           }
           .pt-lg-0,
           .py-lg-0 {
               padding-top: 0!important
           }
           .pr-lg-0,
           .px-lg-0 {
               padding-right: 0!important
           }
           .pb-lg-0,
           .py-lg-0 {
               padding-bottom: 0!important
           }
           .pl-lg-0,
           .px-lg-0 {
               padding-left: 0!important
           }
           .p-lg-1 {
               padding: .25rem!important
           }
           .pt-lg-1,
           .py-lg-1 {
               padding-top: .25rem!important
           }
           .pr-lg-1,
           .px-lg-1 {
               padding-right: .25rem!important
           }
           .pb-lg-1,
           .py-lg-1 {
               padding-bottom: .25rem!important
           }
           .pl-lg-1,
           .px-lg-1 {
               padding-left: .25rem!important
           }
           .p-lg-2 {
               padding: .5rem!important
           }
           .pt-lg-2,
           .py-lg-2 {
               padding-top: .5rem!important
           }
           .pr-lg-2,
           .px-lg-2 {
               padding-right: .5rem!important
           }
           .pb-lg-2,
           .py-lg-2 {
               padding-bottom: .5rem!important
           }
           .pl-lg-2,
           .px-lg-2 {
               padding-left: .5rem!important
           }
           .p-lg-3 {
               padding: 1rem!important
           }
           .pt-lg-3,
           .py-lg-3 {
               padding-top: 1rem!important
           }
           .pr-lg-3,
           .px-lg-3 {
               padding-right: 1rem!important
           }
           .pb-lg-3,
           .py-lg-3 {
               padding-bottom: 1rem!important
           }
           .pl-lg-3,
           .px-lg-3 {
               padding-left: 1rem!important
           }
           .p-lg-4 {
               padding: 1.5rem!important
           }
           .pt-lg-4,
           .py-lg-4 {
               padding-top: 1.5rem!important
           }
           .pr-lg-4,
           .px-lg-4 {
               padding-right: 1.5rem!important
           }
           .pb-lg-4,
           .py-lg-4 {
               padding-bottom: 1.5rem!important
           }
           .pl-lg-4,
           .px-lg-4 {
               padding-left: 1.5rem!important
           }
           .p-lg-5 {
               padding: 3rem!important
           }
           .pt-lg-5,
           .py-lg-5 {
               padding-top: 3rem!important
           }
           .pr-lg-5,
           .px-lg-5 {
               padding-right: 3rem!important
           }
           .pb-lg-5,
           .py-lg-5 {
               padding-bottom: 3rem!important
           }
           .pl-lg-5,
           .px-lg-5 {
               padding-left: 3rem!important
           }
           .m-lg-auto {
               margin: auto!important
           }
           .mt-lg-auto,
           .my-lg-auto {
               margin-top: auto!important
           }
           .mr-lg-auto,
           .mx-lg-auto {
               margin-right: auto!important
           }
           .mb-lg-auto,
           .my-lg-auto {
               margin-bottom: auto!important
           }
           .ml-lg-auto,
           .mx-lg-auto {
               margin-left: auto!important
           }
       }
       
       @media (min-width:1200px) {
           .m-xl-0 {
               margin: 0!important
           }
           .mt-xl-0,
           .my-xl-0 {
               margin-top: 0!important
           }
           .mr-xl-0,
           .mx-xl-0 {
               margin-right: 0!important
           }
           .mb-xl-0,
           .my-xl-0 {
               margin-bottom: 0!important
           }
           .ml-xl-0,
           .mx-xl-0 {
               margin-left: 0!important
           }
           .m-xl-1 {
               margin: .25rem!important
           }
           .mt-xl-1,
           .my-xl-1 {
               margin-top: .25rem!important
           }
           .mr-xl-1,
           .mx-xl-1 {
               margin-right: .25rem!important
           }
           .mb-xl-1,
           .my-xl-1 {
               margin-bottom: .25rem!important
           }
           .ml-xl-1,
           .mx-xl-1 {
               margin-left: .25rem!important
           }
           .m-xl-2 {
               margin: .5rem!important
           }
           .mt-xl-2,
           .my-xl-2 {
               margin-top: .5rem!important
           }
           .mr-xl-2,
           .mx-xl-2 {
               margin-right: .5rem!important
           }
           .mb-xl-2,
           .my-xl-2 {
               margin-bottom: .5rem!important
           }
           .ml-xl-2,
           .mx-xl-2 {
               margin-left: .5rem!important
           }
           .m-xl-3 {
               margin: 1rem!important
           }
           .mt-xl-3,
           .my-xl-3 {
               margin-top: 1rem!important
           }
           .mr-xl-3,
           .mx-xl-3 {
               margin-right: 1rem!important
           }
           .mb-xl-3,
           .my-xl-3 {
               margin-bottom: 1rem!important
           }
           .ml-xl-3,
           .mx-xl-3 {
               margin-left: 1rem!important
           }
           .m-xl-4 {
               margin: 1.5rem!important
           }
           .mt-xl-4,
           .my-xl-4 {
               margin-top: 1.5rem!important
           }
           .mr-xl-4,
           .mx-xl-4 {
               margin-right: 1.5rem!important
           }
           .mb-xl-4,
           .my-xl-4 {
               margin-bottom: 1.5rem!important
           }
           .ml-xl-4,
           .mx-xl-4 {
               margin-left: 1.5rem!important
           }
           .m-xl-5 {
               margin: 3rem!important
           }
           .mt-xl-5,
           .my-xl-5 {
               margin-top: 3rem!important
           }
           .mr-xl-5,
           .mx-xl-5 {
               margin-right: 3rem!important
           }
           .mb-xl-5,
           .my-xl-5 {
               margin-bottom: 3rem!important
           }
           .ml-xl-5,
           .mx-xl-5 {
               margin-left: 3rem!important
           }
           .p-xl-0 {
               padding: 0!important
           }
           .pt-xl-0,
           .py-xl-0 {
               padding-top: 0!important
           }
           .pr-xl-0,
           .px-xl-0 {
               padding-right: 0!important
           }
           .pb-xl-0,
           .py-xl-0 {
               padding-bottom: 0!important
           }
           .pl-xl-0,
           .px-xl-0 {
               padding-left: 0!important
           }
           .p-xl-1 {
               padding: .25rem!important
           }
           .pt-xl-1,
           .py-xl-1 {
               padding-top: .25rem!important
           }
           .pr-xl-1,
           .px-xl-1 {
               padding-right: .25rem!important
           }
           .pb-xl-1,
           .py-xl-1 {
               padding-bottom: .25rem!important
           }
           .pl-xl-1,
           .px-xl-1 {
               padding-left: .25rem!important
           }
           .p-xl-2 {
               padding: .5rem!important
           }
           .pt-xl-2,
           .py-xl-2 {
               padding-top: .5rem!important
           }
           .pr-xl-2,
           .px-xl-2 {
               padding-right: .5rem!important
           }
           .pb-xl-2,
           .py-xl-2 {
               padding-bottom: .5rem!important
           }
           .pl-xl-2,
           .px-xl-2 {
               padding-left: .5rem!important
           }
           .p-xl-3 {
               padding: 1rem!important
           }
           .pt-xl-3,
           .py-xl-3 {
               padding-top: 1rem!important
           }
           .pr-xl-3,
           .px-xl-3 {
               padding-right: 1rem!important
           }
           .pb-xl-3,
           .py-xl-3 {
               padding-bottom: 1rem!important
           }
           .pl-xl-3,
           .px-xl-3 {
               padding-left: 1rem!important
           }
           .p-xl-4 {
               padding: 1.5rem!important
           }
           .pt-xl-4,
           .py-xl-4 {
               padding-top: 1.5rem!important
           }
           .pr-xl-4,
           .px-xl-4 {
               padding-right: 1.5rem!important
           }
           .pb-xl-4,
           .py-xl-4 {
               padding-bottom: 1.5rem!important
           }
           .pl-xl-4,
           .px-xl-4 {
               padding-left: 1.5rem!important
           }
           .p-xl-5 {
               padding: 3rem!important
           }
           .pt-xl-5,
           .py-xl-5 {
               padding-top: 3rem!important
           }
           .pr-xl-5,
           .px-xl-5 {
               padding-right: 3rem!important
           }
           .pb-xl-5,
           .py-xl-5 {
               padding-bottom: 3rem!important
           }
           .pl-xl-5,
           .px-xl-5 {
               padding-left: 3rem!important
           }
           .m-xl-auto {
               margin: auto!important
           }
           .mt-xl-auto,
           .my-xl-auto {
               margin-top: auto!important
           }
           .mr-xl-auto,
           .mx-xl-auto {
               margin-right: auto!important
           }
           .mb-xl-auto,
           .my-xl-auto {
               margin-bottom: auto!important
           }
           .ml-xl-auto,
           .mx-xl-auto {
               margin-left: auto!important
           }
       }
       
       .text-justify {
           text-align: justify!important
       }
       
       .text-nowrap {
           white-space: nowrap!important
       }
       
       .text-truncate {
           overflow: hidden;
           text-overflow: ellipsis;
           white-space: nowrap
       }
       
       .text-left {
           text-align: left!important
       }
       
       .text-right {
           text-align: right!important
       }
       
       .text-center {
           text-align: center!important
       }
       
       @media (min-width:576px) {
           .text-sm-left {
               text-align: left!important
           }
           .text-sm-right {
               text-align: right!important
           }
           .text-sm-center {
               text-align: center!important
           }
       }
       
       @media (min-width:768px) {
           .text-md-left {
               text-align: left!important
           }
           .text-md-right {
               text-align: right!important
           }
           .text-md-center {
               text-align: center!important
           }
       }
       
       @media (min-width:992px) {
           .text-lg-left {
               text-align: left!important
           }
           .text-lg-right {
               text-align: right!important
           }
           .text-lg-center {
               text-align: center!important
           }
       }
       
       @media (min-width:1200px) {
           .text-xl-left {
               text-align: left!important
           }
           .text-xl-right {
               text-align: right!important
           }
           .text-xl-center {
               text-align: center!important
           }
       }
       
       .text-lowercase {
           text-transform: lowercase!important
       }
       
       .text-uppercase {
           text-transform: uppercase!important
       }
       
       .text-capitalize {
           text-transform: capitalize!important
       }
       
       .font-weight-light {
           font-weight: 300!important
       }
       
       .font-weight-normal {
           font-weight: 400!important
       }
       
       .font-weight-bold {
           font-weight: 700!important
       }
       
       .font-italic {
           font-style: italic!important
       }
       
       .text-white {
           color: #fff!important
       }
       
       .text-primary {
           color: #007bff!important
       }
       
       a.text-primary:focus,
       a.text-primary:hover {
           color: #0062cc!important
       }
       
       .text-secondary {
           color: #6c757d!important
       }
       
       a.text-secondary:focus,
       a.text-secondary:hover {
           color: #545b62!important
       }
       
       .text-success {
           color: #28a745!important
       }
       
       a.text-success:focus,
       a.text-success:hover {
           color: #1e7e34!important
       }
       
       .text-info {
           color: #17a2b8!important
       }
       
       a.text-info:focus,
       a.text-info:hover {
           color: #117a8b!important
       }
       
       .text-warning {
           color: #ffc107!important
       }
       
       a.text-warning:focus,
       a.text-warning:hover {
           color: #d39e00!important
       }
       
       .text-danger {
           color: #dc3545!important
       }
       
       a.text-danger:focus,
       a.text-danger:hover {
           color: #bd2130!important
       }
       
       .text-light {
           color: #f8f9fa!important
       }
       
       a.text-light:focus,
       a.text-light:hover {
           color: #dae0e5!important
       }
       
       .text-dark {
           color: #343a40!important
       }
       
       a.text-dark:focus,
       a.text-dark:hover {
           color: #1d2124!important
       }
       
       .text-muted {
           color: #6c757d!important
       }
       
       .text-hide {
           font: 0/0 a;
           color: transparent;
           text-shadow: none;
           background-color: transparent;
           border: 0
       }
       
       .visible {
           visibility: visible!important
       }
       
       .invisible {
           visibility: hidden!important
       }
       
       @media print {
           *,
           ::after,
           ::before {
               text-shadow: none!important;
               box-shadow: none!important
           }
           a:not(.btn) {
               text-decoration: underline
           }
           abbr[title]::after {
               content: " (" attr(title) ")"
           }
           pre {
               white-space: pre-wrap!important
           }
           blockquote,
           pre {
               border: 1px solid #999;
               page-break-inside: avoid
           }
           thead {
               display: table-header-group
           }
           img,
           tr {
               page-break-inside: avoid
           }
           h2,
           h3,
           p {
               orphans: 3;
               widows: 3
           }
           h2,
           h3 {
               page-break-after: avoid
           }
           @page {
               size: a3
           }
           body {
               min-width: 992px!important
           }
           .container {
               min-width: 992px!important
           }
           .navbar {
               display: none
           }
           .badge {
               border: 1px solid #000
           }
           .table {
               border-collapse: collapse!important
           }
           .table td,
           .table th {
               background-color: #fff!important
           }
           .table-bordered td,
           .table-bordered th {
               border: 1px solid #ddd!important
           }
       }
       
       
       /* # sourceMappingURL=bootstrap.min.css.map */ </style>
    <!--EO CSS-->
</head>

<body>
     <header>
        <div class="header-area ">
            <div id="sticky-header" class="main-header-area">
                <div class="container-fluid ">
                    <div class="header_bottom_border">
                        <div class="row align-items-center">
                            <div class="col-xl-3 col-lg-2">
                                <div class="logo">
                                <h1 class="boxed-btn3-line" >Wisdom.</h1>
                                    <a href="index.html">
                                      
                                    </a>
                                </div>
                            </div>
                            <div class="col-12">
                                <div class="mobile_menu d-block d-lg-none"></div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </header>
    <!-- header-end -->

    <!-- slider_area_start -->
    <div class="slider_area">
        <div class="single_slider  d-flex align-items-center slider_bg_1">
            <div class="container">
                <div class="row align-items-center position-relative">
                    <div class="col-lg-9">
                        <div class="slider_text">
                            <h3>Hi there, I am Wisdom <br>
                                <span>Software Developer</span></h3>
                        <a class="boxed-btn3-line" href="#">To Top</a>
                        </div>
                    </div>
                    <div class="my_img d-none d-lg-block">
                        <img src="img/about/my_img.jpg" alt="" height = 400px>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- slider_area_end -->

    <div class="download_area">
        <div class="container">
            <div class="row">
                <div class="col-xl-10">
                    <div class="download_text">
                        <h3>I’m a Software developer based in South Africa, who loves clean and simple code. </h3>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-6 col-md-6">
                    <div class="download_left">
                        <p>My name is Wisdom Mathonisa, I am a 16 year old software developer. I currently study at Curtis Nkondo School of Specialisation.I started being interested in programming when i won a laptop in a math competition and that was my head start. I am passionate about how software works and particularly how it was made thus making me be eager to learn to program. I have learnt several programming languages like Python, C# and Delphi but I specialise mainly in mobile app development with C# and Desktop apps with both Delphi and C#. I also make websites using Html, Css and Javascript.</p>
                        </div>
                </div>
                <div class="col-lg-5 offset-lg-1 col-md-6">
                    <div class="progress_skills">
                        <div class="single_progress">
                            <div class="label d-flex justify-content-between">
                                <span>Mobile App Development</span>
                                <span>90%</span>
                            </div>
                                <div class="progress">
                                        <div class="progress-bar " role="progressbar" style="width: 90%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                      </div>
                        </div>
                        <div class="single_progress">
                                <div class="label d-flex justify-content-between">
                                        <span>Desktop App Development</span>
                                        <span>70%</span>
                                    </div>
                                <div class="progress">
                                        <div class="progress-bar " role="progressbar" style="width: 70%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                      </div>
                        </div>
                        <div class="single_progress">
                                <div class="label d-flex justify-content-between">
                                        <span>Web Development</span>
                                        <span>45%</span>
                                    </div>
                                <div class="progress">
                                        <div class="progress-bar" role="progressbar" style="width: 45%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                                      </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- service_area start  -->
    <div class="service_area">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="section_title mb-50">
                        <h3>My Services</h3>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-4 col-md-6">
                    <div class="single_service text-center">
                        <div class="icon">
                            <img src="img/svg_icon/1.svg" alt="">
                        </div>
                        <h3>
                                Mobile App Development
                        </h3>
                        <p> Make your app a great reality with beautiful user friendly interfaces and wonderful interactiveness.</p> </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_service text-center">
                        <div class="icon">
                            <img src="img/svg_icon/2.svg" alt="">
                        </div>
                        <h3>
                                Web Development
                        </h3>
                        <p> Want to make a website for you or your company? This is the place.</p> </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_service text-center">
                        <div class="icon">
                            <img src="img/svg_icon/3.svg" alt="">
                        </div>
                        <h3>
                                Desktop App Development
                        </h3>
                        <p>I make desktop apps worthwhile with beautiful interfaces and error free apps with speed effectiency.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- service_area end  -->

    <!-- gallery_area start  -->
    <div class="gallery_area">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="section_title mb-50">
                        <h3>My Achivements</h3>
                    </div>
                </div>
            </div>
            <div class="row justify-content-center">
                <div class="col-xl-10 col-lg-10">
                    <div class="row">
                        <div class="col-xl-6 col-lg-6 col-md-6">
                            <div class="single_gallery">
                                <div class="thumb">
                                   <img src="img/about/mill.jpg" >
                                </div>
                                <div class="gallery_heading">
                                    <span><h4>Siyavula #1 Million Maths Competition Winner</h4></span>
                                 
                                </div>
                            </div>
                            <div class="single_gallery">
                                <div class="thumb">
                                    <img src="img/about/html.jpg" >
                                </div>
                                <div class="gallery_heading">
                                    <span><h4>Sololearn HTML Certification</h4></span>
                                  </div>
                            </div>
                        </div>
                        <div class="col-xl-6 col-lg-6 col-md-6">
                            <div class="single_gallery">
                                <div class="thumb">
                                    <img src="img/about/csharp.jpg" ></div>
                                <div class="gallery_heading">
                                    <span><h4>Sololearn C# Certification</h4></span>
                                     </div>
                            </div>
                            <div class="single_gallery">
                                <div class="thumb">
                                    <img src="img/about/Python.jpg" >
                                </div>
                                <div class="gallery_heading">
                                
                                    <span><h4>Sololearn Python Certification</h4></span>
                                  
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-12">
                            <div class="more_works">
                                    <a class="boxed-btn3-line" href="#">To Top</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- gallery_area end  -->
   <div class="gallery_area">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="section_title mb-50">
                        <h3>My Likes</h3>
                    </div>
                </div>
            </div>
            <div class="row justify-content-center">
                <div class="col-xl-10 col-lg-10">
                    <div class="row">
                        <div class="col-xl-6 col-lg-6 col-md-6">
                            <div class="single_gallery">
                                <div class="thumb">
                                   <img src="chess.png" >
                                </div>
                                <div class="gallery_heading">
                                    <span><h4>Chess</h4></span>
                                 
                                </div>
                            </div>
                            <div class="single_gallery">
                                <div class="thumb">
                                    <img src="game.png" >
                                </div>
                                <div class="gallery_heading">
                                    <span><h4>Gaming</h4></span>
                                  </div>
                            </div>
                        </div>
                        <div class="col-xl-6 col-lg-6 col-md-6">
                            <div class="single_gallery">
                                <div class="thumb">
                                    <img src="space.jpg" ></div>
                                <div class="gallery_heading">
                                    <span><h4>Space Exploring</h4></span>
                                     </div>
                            </div>
                            <div class="single_gallery">
                                <div class="thumb">
                                    <img src="eth.png" >
                                </div>
                                <div class="gallery_heading">
                                
                                    <span><h4>Ethical hacking</h4></span>
                                  
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-12">
                            <div class="more_works">
                                    <a class="boxed-btn3-line" href="#">To Top</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <!-- footer start -->
    <footer class="footer">
        <div class="footer_top">
            <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="section_title mb-50">
                        <h3>Contact Details</h3>
                    </div>
                </div>
            </div>
        
                <div class="row">
                    <div class="col-lg-8">
                        
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-3">
                        <div class="single_links d-flex justify-content-between align-items-center">
                            <span>Cell : 0631094298</span>
                            
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="single_links d-flex justify-content-between align-items-center">
                            <span>Email : wisdomwiseman9 @gmail.com</span>
                            
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="single_links d-flex justify-content-between align-items-center">
                            <span>Linkedin : Wisdom Mathonisa</span>
                            
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="single_links d-flex justify-content-between align-items-center">
                            <span>Facebook : Wisdom Wiseman</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="copy-right_text">
            <div class="container">
                <div class="footer_border"></div>
                <div class="row">
                    <div class="col-xl-12">
                        <p class="copy_right text-center">
                         
Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | Wisdom. |

                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>
    <!--/ footer end  -->
</body>

</html>
