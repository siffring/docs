---
title: craft\console\CallableAction
code:
  - php
  - twig
---

# CallableAction

Type

:   Class

Namespace

:   craft\console

Inherits

:   [craft\console\CallableAction](craft-console-callableaction.md) &raquo;
[yii\base\Action](https://www.yiiframework.com/doc/api/2.0/yii-base-action) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable)

Since

:   3.2.0



Class CallableAction





[View source](https://github.com/craftcms/cms/blob/master/src/console/CallableAction.php)


## Public Properties

| Property                                                                                                                   | Description
| -------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component") | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [callable](craft-console-callableaction.md#callable)                                                                       | [callable](http://php.net/language.types.callable) – The action callable
| [controller](https://www.yiiframework.com/doc/api/2.0/yii-base-action#$controller-detail "Defined by yii\base\Action")     | [yii\base\Controller](https://www.yiiframework.com/doc/api/2.0/yii-base-controller), [yii\web\Controller](https://www.yiiframework.com/doc/api/2.0/yii-web-controller), [yii\console\Controller](https://www.yiiframework.com/doc/api/2.0/yii-console-controller) – The controller that owns this action
| [id](https://www.yiiframework.com/doc/api/2.0/yii-base-action#$id-detail "Defined by yii\base\Action")                     | [string](http://php.net/language.types.string) – ID of the action
| [uniqueId](https://www.yiiframework.com/doc/api/2.0/yii-base-action#$uniqueId-detail "Defined by yii\base\Action")         | [string](http://php.net/language.types.string) – The unique ID of this action among the whole application.

### `callable`



Type

:   [callable](http://php.net/language.types.callable)



The action callable



[View source](https://github.com/craftcms/cms/blob/master/src/console/CallableAction.php#L24)







## Public Methods

| Method                                                                                                                                      | Description
| ------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__call()-detail "Defined by yii\base\BaseObject")                   | Calls the named method which is not a class method.
| [__clone()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__clone()-detail "Defined by yii\base\Component")                   | This method is called after the object is created by cloning an existing one.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")         | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__get()-detail "Defined by yii\base\BaseObject")                     | Returns the value of an object property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__isset()-detail "Defined by yii\base\BaseObject")                 | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__set()-detail "Defined by yii\base\BaseObject")                     | Sets value of an object property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__unset()-detail "Defined by yii\base\BaseObject")                 | Sets an object property to null.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")     | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")   | Attaches a list of behaviors to the component.
| [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail "Defined by yii\base\Component")               | Returns a list of behaviors that this component should behave as.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canGetProperty()-detail "Defined by yii\base\BaseObject")   | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canSetProperty()-detail "Defined by yii\base\BaseObject")   | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")             | Returns the fully qualified name of this class.
| [detachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehavior()-detail "Defined by yii\base\Component")     | Detaches a behavior from the component.
| [detachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehaviors()-detail "Defined by yii\base\Component")   | Detaches all behaviors from the component.
| [ensureBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#ensureBehaviors()-detail "Defined by yii\base\Component")   | Makes sure that the behaviors declared in [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail) are attached to this component.
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")           | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")         | Returns all behaviors attached to this component.
| [getUniqueId()](https://www.yiiframework.com/doc/api/2.0/yii-base-action#getUniqueId()-detail "Defined by yii\base\Action")                 | Returns the unique ID of this action among the whole application.
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component") | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")             | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")         | Returns a value indicating whether a property is defined.
| [init()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#init()-detail "Defined by yii\base\BaseObject")                       | Initializes the object.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                           | Detaches an existing event handler from this component.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                             | Attaches an event handler to an event.
| [runWithParams()](craft-console-callableaction.md#method-runwithparams)                                                                     | Runs this action with the specified parameters.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                   | Triggers an event.

### `runWithParams()`





Runs this action with the specified parameters.

This method is mainly invoked by the controller.


[View source](https://github.com/craftcms/cms/blob/master/src/console/CallableAction.php#L33-L42)


#### Arguments

- `$params` ([array](http://php.net/language.types.array)) – Action parameters

#### Returns

`mixed` – The result of the action





## Protected Methods

| Method                                                                                                                  | Description
| ----------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------
| [afterRun()](https://www.yiiframework.com/doc/api/2.0/yii-base-action#afterRun()-detail "Defined by yii\base\Action")   | This method is called right after `run()` is executed.
| [beforeRun()](https://www.yiiframework.com/doc/api/2.0/yii-base-action#beforeRun()-detail "Defined by yii\base\Action") | This method is called right before `run()` is executed.





