# Angular Modularity System 

## Angular modules or NgModules

Every Angular app has at least one module, the root module, conventionally named AppModule

Angular application often have other feature modules, standing as cohesive code blocks dedicated to an application domain, a workflow or a closely related set of capabilities

All Angular modules are classes with an @NgModule decorator whitch attaches relevent metadata

The most important properties of the metadata object provided to the @NgModule decorator are:
	- declarations: view classes beloning to a module (Components, directives and pipes)
	- exports: declarations that should be usable in the component templates of other modules
	- imports: other modules whose exported classes are neded by templates declared in this module
	- providers: this module contributions to the global collection of services
	- bootstrap: the main 'root' component application view which hosts all other views

Angular modules are completly different than the JavaScript module system for managing collections of JavaScript objects.

Root Module: 

import { NgModule }      from '@angular/core';
import { BrowserModule } from '@angular/platform-browser';
@NgModule({
  imports:      [ BrowserModule ],
  providers:    [ Logger ],
  declarations: [ AppComponent ],
  exports:      [ AppComponent ],
  bootstrap:    [ AppComponent ]
})
export class AppModule { }
