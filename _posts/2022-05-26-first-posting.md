---
layout: post
title: "깃허브 블로그 만들기"
date: 2022-05-26 12:00
category: category2
icon: git
keywords: tag1, tag2
image: 1.jpg
preview: 0
---

1. [Ruby 설치](#ruby-설치)
2. [jekyll 설치](#jekyll-설치)
3. [jekyll 설치 확인](#jekyll-설치-확인)
4. [서버 실행 테스트](#서버-실행-테스트)
5. [error 발생했을때](#error-발생했을때)
6. [서버실행확인 주소](#서버실행확인-주소)
7. [깃허브 블로그 생성](#깃허브-블로그-생성)
   - [템플릿 선택](#템플릿-선택)
   - [내 깃허브 repository 생성](#내-깃허브-repository-생성)
   - [import a repository](#import-a-repository-에-복사한url-붙여넣기)
   - [reposiory name : user_id.github.io](#repository-name--본인아이디githubio)
   - [https://user_id.github.io 확인](#https본인아이디githubio-확인)
   - [git clone](#클론으로-디렉터리-가져오기)
   - [post 디렉터리에서 yyyy-mm-dd-title.md 로 포스팅](#_post-에서-md-파일-생성하여-포스팅)

## Ruby 설치

- (https://rubyinstaller.org/downloads/)
- WITH DEVKIT에서 맞는 버전 설치

## jekyll 설치

- Start Command Prompt with Ruby 실행
- gem install jekyll
- gem install minima
- gem install bundler
- gem install jekyll-feed
- gem install tzinfo-data

## jekyll 설치 확인

- jekyll -v

## 서버 실행 테스트

- jekyll new 블로그이름
- jekyll serve(생성한 블로그디렉터리에서)

## error 발생했을때

- bundle add webrick
- jekyll serve

## 서버실행확인 주소

- (http://127.0.0.1:4000/)

## 깃허브 블로그 생성

## 템플릿 선택

)http://jekyllthemes.org/)
해당템플릿 깃허브 페이지에서 url 복사

## 내 깃허브 repository 생성

## import a repository 에 복사한url 붙여넣기

## repository name : 본인아이디.github.io

## https://본인아이디.github.io 확인

## 클론으로 디렉터리 가져오기

git clone

## \_post 에서 md 파일 생성하여 포스팅

yyyy-mm-dd-title.md
