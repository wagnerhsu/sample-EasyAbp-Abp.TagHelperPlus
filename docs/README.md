# Abp.TagHelperPlus

[![NuGet](https://img.shields.io/nuget/v/EasyAbp.Abp.TagHelperPlus.svg?style=flat-square)](https://www.nuget.org/packages/EasyAbp.Abp.TagHelperPlus)
[![NuGet Download](https://img.shields.io/nuget/dt/EasyAbp.Abp.TagHelperPlus.svg?style=flat-square)](https://www.nuget.org/packages/EasyAbp.Abp.TagHelperPlus)

An Abp MVC UI tag-helper enhancement module to enhance ABP built-in tag-helpers and provide new tag-helpers such as rich text editor, advanced selector, and more.

## Online Demo

We have launched an online demo for this module: [https://taghelper.samples.easyabp.io](https://taghelper.samples.easyabp.io)

## Installation

1. Install the following NuGet packages. ([see how](https://github.com/EasyAbp/EasyAbpGuide/blob/master/How-To.md#add-nuget-packages))

    * EasyAbp.Abp.TagHelperPlus

1. Add `DependsOn(typeof(AbpTagHelperPlusModule))` attribute to configure the module dependencies. ([see how](https://github.com/EasyAbp/EasyAbpGuide/blob/master/How-To.md#add-module-dependencies))

## Features

### EasySelector

Improve the abp-select to support paged items and search. ([see demo](https://github.com/EasyAbp/Abp.TagHelperPlus/blob/master/host/EasyAbp.Abp.TagHelperPlus.Web.Unified/Pages/Books/Book/ViewModels/CreateEditBookViewModel.cs#L13-L18))

![CacheItems](/docs/images/EasySelector/EditBook.png)

## Road map

- [x] Easy Selector
- [ ] Items sorter
- [ ] Rich text editor
