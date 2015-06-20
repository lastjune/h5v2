h5v2
====

An unfinished web component, npm-compatible version of h5Validate, the popular HTML5 form validation library.

This is a complete rewrite of the popular but outdated [h5Validate](https://github.com/ericelliott/h5Validate).

It should pass a similar suite of unit tests.

## The following changes are planned

* Implement as a React component (compile a generic web component version) instead of a jQuery plugin.
* Break the dependence on jQuery.
* This is a next-gen validation lib. Use ES6 modules + Browserify transpile.
* Implement modular validations.
* Allow API access to mark a field invalid and set the error message (to allow complex model validations without maintaining any model state on the DOM).
* Support the new HTML5 input types as much as possible.
* Create our own form element
  * Focus the first invalid field on **whole form validation errors**
* Create our own field element with a required label (see [Accessible Client Side Form Validation](http://www.deque.com/blog/accessible-client-side-form-validation-html5/)).
* [Ease support for WAI-ARIA](http://www.deque.com/blog/accessible-client-side-form-validation-html5-wai-aria/)
