# City

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.22.

## Introduction

这是一个Angular组件练习项目

## 组件使用过程

 1.新建项目，然后用AngularCLI来创建自己的组件，新建完成后app.moudle.ts中已经组成好了。
        ng g c [name]
 2.编辑component，通过参数radioValue和ngIf指令来控制显示对应的三个组件
       <app-beijing *ngIf="radioValue == 'beijing'"></app-beijing>

## Development server

npm install

npm start

Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
