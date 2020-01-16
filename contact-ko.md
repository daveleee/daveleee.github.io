---
layout: page
title: 문의하기
lang: ko
permalink: /contact/
description: 우리에게 무언가 물어보고 싶으신가요?
background: '/img/bg-contact.jpg'
form: true
---

<p>우리에게 무언가 문의하실 일이 있으시다면, 아래에 양식을 통해 문의주세요. 빠른 시일 이내에 연락 드리겠습니다.</p>
<form action="https://formspree.io/mgeonzde" method="post">
  <input type="hidden" name="_subject" value="깃허브 블로그에서 새로운 메일이 왔습니다." />
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Name</label>
      <input type="text" class="form-control" placeholder="이름" name="name" id="name" required data-validation-required-message="Please enter your name.">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Email Address</label>
      <input type="email" class="form-control" placeholder="이메일 주소" name="email" id="email" required data-validation-required-message="Please enter your email address.">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group col-xs-12 floating-label-form-group controls">
      <label>Phone Number</label>
      <input type="tel" class="form-control" placeholder="연락처" name="phone" id="phone" required data-validation-required-message="Please enter your phone number.">
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <div class="control-group">
    <div class="form-group floating-label-form-group controls">
      <label>Message</label>
      <textarea rows="5" class="form-control" placeholder="메세지" name="message" id="message" required data-validation-required-message="Please enter a message."></textarea>
      <p class="help-block text-danger"></p>
    </div>
  </div>
  <br>
  <div id="success"></div>
  <div class="form-group">
    <button type="submit" class="btn btn-primary" id="sendMessageButton">전송</button>
  </div>
</form>
