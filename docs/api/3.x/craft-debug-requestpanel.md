---
title: craft\debug\RequestPanel
code:
  - php
  - twig
---

# RequestPanel

Type

:   Class

Namespace

:   craft\debug

Inherits

:   [craft\debug\RequestPanel](craft-debug-requestpanel.md) &raquo;
[yii\debug\panels\RequestPanel](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panels-requestpanel) &raquo;
[yii\debug\Panel](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable)

Since

:   3.1.1



Debugger panel that collects and displays request data.





[View source](https://github.com/craftcms/cms/blob/master/src/debug/RequestPanel.php)


## Public Properties

| Property                                                                                                                                                                          | Description
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------
| [actions](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$actions-detail "Defined by yii\debug\Panel")                                     | [array](http://php.net/language.types.array) – Array of actions to add to the debug modules default controller.
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component")                                                        | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [data](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$data-detail "Defined by yii\debug\Panel")                                           | `mixed` – Data associated with panel
| [detail](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$detail-detail "Defined by yii\debug\Panel")                                       | [string](http://php.net/language.types.string) – Content that is displayed in debugger detail view
| [displayVars](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panels-requestpanel#$displayVars-detail "Defined by yii\debug\panels\RequestPanel") | [array](http://php.net/language.types.array) – List of the PHP predefined variables that are allowed to be displayed in the request panel.
| [id](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$id-detail "Defined by yii\debug\Panel")                                               | [string](http://php.net/language.types.string) – Panel unique identifier.
| [module](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$module-detail "Defined by yii\debug\Panel")                                       | [yii\debug\Module](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-module)
| [name](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$name-detail "Defined by yii\debug\Panel")                                           | [string](http://php.net/language.types.string) – Name of the panel
| [summary](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$summary-detail "Defined by yii\debug\Panel")                                     | [string](http://php.net/language.types.string) – Content that is displayed at debug toolbar
| [tag](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$tag-detail "Defined by yii\debug\Panel")                                             | [string](http://php.net/language.types.string) – Request data set identifier.
| [url](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$url-detail "Defined by yii\debug\Panel")                                             | [string](http://php.net/language.types.string) – URL pointing to panel detail view



## Protected Properties

| Property                                                                                                                                  | Description
| ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [error](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#$error-detail "Defined by yii\debug\Panel") | [yii\debug\FlattenException](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-flattenexception), [null](http://php.net/language.types.null) – Error while saving the panel



## Public Methods

| Method                                                                                                                                                     | Description
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__call()-detail "Defined by yii\base\BaseObject")                                  | Calls the named method which is not a class method.
| [__clone()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__clone()-detail "Defined by yii\base\Component")                                  | This method is called after the object is created by cloning an existing one.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")                        | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__get()-detail "Defined by yii\base\BaseObject")                                    | Returns the value of an object property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__isset()-detail "Defined by yii\base\BaseObject")                                | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__set()-detail "Defined by yii\base\BaseObject")                                    | Sets value of an object property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__unset()-detail "Defined by yii\base\BaseObject")                                | Sets an object property to null.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")                    | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")                  | Attaches a list of behaviors to the component.
| [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail "Defined by yii\base\Component")                              | Returns a list of behaviors that this component should behave as.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canGetProperty()-detail "Defined by yii\base\BaseObject")                  | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canSetProperty()-detail "Defined by yii\base\BaseObject")                  | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                            | Returns the fully qualified name of this class.
| [detachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehavior()-detail "Defined by yii\base\Component")                    | Detaches a behavior from the component.
| [detachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehaviors()-detail "Defined by yii\base\Component")                  | Detaches all behaviors from the component.
| [ensureBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#ensureBehaviors()-detail "Defined by yii\base\Component")                  | Makes sure that the behaviors declared in [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail) are attached to this component.
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")                          | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")                        | Returns all behaviors attached to this component.
| [getDetail()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#getDetail()-detail "Defined by yii\debug\Panel")       |
| [getError()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#getError()-detail "Defined by yii\debug\Panel")         |
| [getName()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#getName()-detail "Defined by yii\debug\Panel")           |
| [getSummary()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#getSummary()-detail "Defined by yii\debug\Panel")     |
| [getTraceLine()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#getTraceLine()-detail "Defined by yii\debug\Panel") | Returns a trace line
| [getUrl()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#getUrl()-detail "Defined by yii\debug\Panel")             |
| [hasError()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#hasError()-detail "Defined by yii\debug\Panel")         |
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component")                | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")                            | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")                        | Returns a value indicating whether a property is defined.
| [init()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#init()-detail "Defined by yii\base\BaseObject")                                      | Initializes the object.
| [isEnabled()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#isEnabled()-detail "Defined by yii\debug\Panel")       | Checks whether this panel is enabled.
| [load()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#load()-detail "Defined by yii\debug\Panel")                 | Loads data into the panel
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                                          | Detaches an existing event handler from this component.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                                            | Attaches an event handler to an event.
| [save()](craft-debug-requestpanel.md#method-save)                                                                                                          |
| [setError()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#setError()-detail "Defined by yii\debug\Panel")         |
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                                  | Triggers an event.

### `save()`










[View source](https://github.com/craftcms/cms/blob/master/src/debug/RequestPanel.php#L23-L28)








## Protected Methods

| Method                                                                                                                                                                             | Description
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------
| [getFlashes()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panels-requestpanel#getFlashes()-detail "Defined by yii\debug\panels\RequestPanel") | Getting flash messages without deleting them or touching deletion counters
| [getLogMessages()](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/api/2.2/yii-debug-panel#getLogMessages()-detail "Defined by yii\debug\Panel")                     | Gets messages from log target and filters according to their categories and levels.





