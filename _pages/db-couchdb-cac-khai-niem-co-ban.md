---
permalink: "/db-couchdb-cac-khai-niem-co-ban/"
layout: page
title: Các khái niệm cơ bản về CouchDB
---


## CouchDB là gì ?

* CouchDB là 1 sơ sở dữ liệu dạng NoSQL mã nguồn mở database lưu trữ dữ liệu dạng document/JSON.
* CouchDB được thiết kế nhắm tới tính dễ sử dụng và phục vụ cho môi trường web.

## Tại sao chúng ta lại cần CouchDB ?

* CouchDB có API dạng RESTFul giúp cho việc giao tiếp với cơ sở dữ liệu được đơn giản.
* Các RESTFul API rất trực quan và dễ thao tác.
* Dữ liệu được lưu dưới cấu trúc document rất mềm dẻo, chúng ta không cần phải lo lắng về cấu trúc dữ liệu.
* Map/reduce giúp việc lọc, tìm, tổng hợp dữ liệu dễ hơn bao giờ hết.
* Nhân bản / đồng bộ là sức mạnh đặc biệt của CouchDB mà hiếm database nào có.

## Mô hình dữ liệu

* Database là cấu trúc dữ liệu lớn nhất của CouchDB.
* Mỗi database là 1 danh sách các document độc lập.
* Document bao gồm dữ liệu người dùng thao tác lẫn thông tin về phiên bản của dữ liệu để tiện việc merge dữ liệu.
* CouchDB sử dụng cơ chế phiên bản hoá dữ liệu để tránh tình trạng khoá dữ liệu khi đang ghi.
