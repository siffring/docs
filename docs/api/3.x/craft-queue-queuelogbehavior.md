---
title: craft\queue\QueueLogBehavior
code:
  - php
  - twig
---

# QueueLogBehavior

Type

:   Class

Namespace

:   craft\queue

Inherits

:   [craft\queue\QueueLogBehavior](craft-queue-queuelogbehavior.md) &raquo;
[craft\queue\VerboseBehavior](craft-queue-verbosebehavior.md) &raquo;
[yii\queue\cli\VerboseBehavior](https://github.com/yiisoft/yii2-queue/blob/master/src/cli/VerboseBehavior.php) &raquo;
[yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable)

Since

:   3.0.0



Queue Log Behavior





[View source](https://github.com/craftcms/cms/blob/master/src/queue/QueueLogBehavior.php)


## Public Properties

| Property                                                                                                                                            | Description
| --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------
| [command](https://github.com/yiisoft/yii2-queue/blob/master/src/cli/VerboseBehavior.php#$command-detail "Defined by yii\queue\cli\VerboseBehavior") | [yii\console\Controller](https://www.yiiframework.com/doc/api/2.0/yii-console-controller)
| [owner](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior#$owner-detail "Defined by yii\base\Behavior")                                    | [yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component), [null](http://php.net/language.types.null) – The owner of this behavior





## Public Methods

| Method                                                                                                                                                         | Description
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__call()-detail "Defined by yii\base\BaseObject")                                      | Calls the named method which is not a class method.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")                            | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__get()-detail "Defined by yii\base\BaseObject")                                        | Returns the value of an object property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__isset()-detail "Defined by yii\base\BaseObject")                                    | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__set()-detail "Defined by yii\base\BaseObject")                                        | Sets value of an object property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__unset()-detail "Defined by yii\base\BaseObject")                                    | Sets an object property to null.
| [afterError()](craft-queue-queuelogbehavior.md#method-aftererror)                                                                                              |
| [afterExec()](craft-queue-queuelogbehavior.md#method-afterexec)                                                                                                |
| [attach()](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior#attach()-detail "Defined by yii\base\Behavior")                                          | Attaches the behavior object to the component.
| [beforeExec()](craft-queue-queuelogbehavior.md#method-beforeexec)                                                                                              |
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canGetProperty()-detail "Defined by yii\base\BaseObject")                      | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canSetProperty()-detail "Defined by yii\base\BaseObject")                      | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                                | Returns the fully qualified name of this class.
| [detach()](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior#detach()-detail "Defined by yii\base\Behavior")                                          | Detaches the behavior object from the component.
| [events()](craft-queue-queuelogbehavior.md#method-events)                                                                                                      | Declares event handlers for the [owner](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior#$owner-detail)'s events.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")                                | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")                            | Returns a value indicating whether a property is defined.
| [init()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#init()-detail "Defined by yii\base\BaseObject")                                          | Initializes the object.
| [workerStart()](https://github.com/yiisoft/yii2-queue/blob/master/src/cli/VerboseBehavior.php#workerStart()-detail "Defined by yii\queue\cli\VerboseBehavior") |
| [workerStop()](https://github.com/yiisoft/yii2-queue/blob/master/src/cli/VerboseBehavior.php#workerStop()-detail "Defined by yii\queue\cli\VerboseBehavior")   |

### `afterError()`














[View source](https://github.com/craftcms/cms/blob/master/src/queue/QueueLogBehavior.php#L69-L81)


#### Arguments

- `$event` ([yii\queue\ExecEvent](https://github.com/yiisoft/yii2-queue/blob/master/src/ExecEvent.php))




### `afterExec()`














[View source](https://github.com/craftcms/cms/blob/master/src/queue/QueueLogBehavior.php#L60-L64)


#### Arguments

- `$event` ([yii\queue\ExecEvent](https://github.com/yiisoft/yii2-queue/blob/master/src/ExecEvent.php))




### `beforeExec()`










[View source](https://github.com/craftcms/cms/blob/master/src/queue/QueueLogBehavior.php#L47-L55)


#### Arguments

- `$event` ([yii\queue\ExecEvent](https://github.com/yiisoft/yii2-queue/blob/master/src/ExecEvent.php))




### `events()`





Declares event handlers for the [owner](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior#$owner-detail)'s events.



Child classes may override this method to declare what PHP callbacks should
be attached to the events of the [owner](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior#$owner-detail) component.

The callbacks will be attached to the [owner](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior#$owner-detail)'s events when the behavior is
attached to the owner; and they will be detached from the events when
the behavior is detached from the component.

The callbacks can be any of the following:

- method in this behavior: `'handleClick'`, equivalent to `[$this, 'handleClick']`
- object method: `[$object, 'handleClick']`
- static method: `['Page', 'handleClick']`
- anonymous function: `function ($event) { ... }`

The following is an example:

```php
[
    Model::EVENT_BEFORE_VALIDATE => 'myBeforeValidate',
    Model::EVENT_AFTER_VALIDATE => 'myAfterValidate',
]
```




[View source](https://github.com/craftcms/cms/blob/master/src/queue/QueueLogBehavior.php#L35-L42)



#### Returns

[array](http://php.net/language.types.array) – Events (array keys) and the corresponding event handler methods (array values).





## Protected Methods

| Method                                                                                                                                                               | Description
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -----------
| [formatDuration()](https://github.com/yiisoft/yii2-queue/blob/master/src/cli/VerboseBehavior.php#formatDuration()-detail "Defined by yii\queue\cli\VerboseBehavior") |
| [jobTitle()](craft-queue-verbosebehavior.md#method-jobtitle "Defined by craft\queue\VerboseBehavior")                                                                |





