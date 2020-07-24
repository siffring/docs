---
title: craft\events\ConfigEvent
code:
  - php
  - twig
---

# ConfigEvent

Type

:   Class

Namespace

:   craft\events

Inherits

:   [craft\events\ConfigEvent](craft-events-configevent.md) &raquo;
[yii\base\Event](https://www.yiiframework.com/doc/api/2.0/yii-base-event) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable)

Since

:   3.1.0



Config event class.





[View source](https://github.com/craftcms/cms/blob/master/src/events/ConfigEvent.php)


## Public Properties

| Property                                                                                                       | Description
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [data](https://www.yiiframework.com/doc/api/2.0/yii-base-event#$data-detail "Defined by yii\base\Event")       | `mixed` – The data that is passed to [yii\base\Component::on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail) when attaching an event handler.
| [handled](https://www.yiiframework.com/doc/api/2.0/yii-base-event#$handled-detail "Defined by yii\base\Event") | [boolean](http://php.net/language.types.boolean) – Whether the event is handled.
| [name](https://www.yiiframework.com/doc/api/2.0/yii-base-event#$name-detail "Defined by yii\base\Event")       | [string](http://php.net/language.types.string) – The event name.
| [newValue](craft-events-configevent.md#newvalue)                                                               | [array](http://php.net/language.types.array) – The new config item value
| [oldValue](craft-events-configevent.md#oldvalue)                                                               | [array](http://php.net/language.types.array) – The old config item value
| [path](craft-events-configevent.md#path)                                                                       | [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – The config path being processed
| [sender](https://www.yiiframework.com/doc/api/2.0/yii-base-event#$sender-detail "Defined by yii\base\Event")   | [object](http://php.net/language.types.object) – The sender of this event.
| [tokenMatches](craft-events-configevent.md#tokenmatches)                                                       | [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null) – Any parts of the path that were matched by `{uid}` tokens.

### `newValue`



Type

:   [array](http://php.net/language.types.array)



The new config item value



[View source](https://github.com/craftcms/cms/blob/master/src/events/ConfigEvent.php#L33)



### `oldValue`



Type

:   [array](http://php.net/language.types.array)



The old config item value



[View source](https://github.com/craftcms/cms/blob/master/src/events/ConfigEvent.php#L28)



### `path`



Type

:   [string](http://php.net/language.types.string), [null](http://php.net/language.types.null)



The config path being processed



[View source](https://github.com/craftcms/cms/blob/master/src/events/ConfigEvent.php#L23)



### `tokenMatches`



Type

:   [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null)



Any parts of the path that were matched by `{uid}` tokens.
This wil be populated if the handler was registered using [craft\services\ProjectConfig::registerChangeEventHandler()](craft-services-projectconfig.md#method-registerchangeeventhandler),
or one of its shortcut methods.



[View source](https://github.com/craftcms/cms/blob/master/src/events/ConfigEvent.php#L40)







## Public Methods

| Method                                                                                                                                    | Description
| ----------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__call()-detail "Defined by yii\base\BaseObject")                 | Calls the named method which is not a class method.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")       | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__get()-detail "Defined by yii\base\BaseObject")                   | Returns the value of an object property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__isset()-detail "Defined by yii\base\BaseObject")               | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__set()-detail "Defined by yii\base\BaseObject")                   | Sets value of an object property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__unset()-detail "Defined by yii\base\BaseObject")               | Sets an object property to null.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canGetProperty()-detail "Defined by yii\base\BaseObject") | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canSetProperty()-detail "Defined by yii\base\BaseObject") | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")           | Returns the fully qualified name of this class.
| [hasHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-event#hasHandlers()-detail "Defined by yii\base\Event")                 | Returns a value indicating whether there is any handler attached to the specified class-level event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")           | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")       | Returns a value indicating whether a property is defined.
| [init()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#init()-detail "Defined by yii\base\BaseObject")                     | Initializes the object.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-event#off()-detail "Defined by yii\base\Event")                                 | Detaches an event handler from a class-level event.
| [offAll()](https://www.yiiframework.com/doc/api/2.0/yii-base-event#offAll()-detail "Defined by yii\base\Event")                           | Detaches all registered class-level event handlers.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-event#on()-detail "Defined by yii\base\Event")                                   | Attaches an event handler to a class-level event.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-event#trigger()-detail "Defined by yii\base\Event")                         | Triggers a class-level event.







