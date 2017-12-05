# laravel-blade-phpstorm-live-template
PhpStorm Live templates let you insert frequently-used or custom code constructs into your source code file quickly, efficiently, and accurately.

This repo contains live templates for frequently-used Laravel Blade directives.

![Demo](img/demo.gif)

##How to install
1) Download and copy the *Laravel-Blade.xml* file to your templates folder:

* Windows: `<your home directory>\.<product name><version number>\config\templates`
* Linux: `~\.<product name><version number>\config\templates`
* OS X: `~/Library/Preferences/<product name><version number>/templates`

e.g. `~/Library/Preferences/PhpStorm2017.2/templates` on OS X for PhpStorm 2017

2) Restart PhpStorm.

3) To see all templates, go to *Preferences->Live Templates* and expand the Template Group.

## Templates
* **@elseif** : Blade @elseif
* **@for** : Blade @for
* **@foreach** : Blade @foreach
* **@if** : Blade @if
* **@ifelse** : Blade @ifelse
* **@include** : Blade @include
* **@layout** : Blade template skeleton
* **@section** : Blade @section
* **@while** : Blade @while
* **{{** : Blade {{ echo data }}
* **@yield** : Blade @yield
* **@extends** : Blade @extends
* **@sectionx** : Blade @section extended
* **{{{** : Blade {{{ echo escaped data }}}
* **@unless** : Blade @unless
* **{{--** : Blade comments
* **@forelse** : Blade @forelse
* **{!!** : Blade {!! echo raw data !!}
* **@component** : Blade @component
* **component** : Blade component scaffold
* **@auth** : Blade @auth
* **@guest** : Blade @guest
* **@switch** : Blade @switch
* **@includeWhen** : Blade @includeWhen
* **@each** : Blade @each
* **@push** : Blade @push
* **@stack** : Blade @stack
* **@inject** : Blade @inject
* **@can** : Blade @can
* **@cannot** : Blade @cannot
* **@verbatim** : Blade @verbatim
* **@isset** : Blade @isset
* **@empty** : Blade @empty
* **mix** : Laravel's global mix function
* **@lang** : Blade @lang    