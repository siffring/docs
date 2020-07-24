---
title: craft\services\SystemSettings
code:
  - php
  - twig
---

# SystemSettings

Type

:   Class

Namespace

:   craft\services

Inherits

:   [craft\services\SystemSettings](craft-services-systemsettings.md) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable)

Since

:   3.0.0

Deprecated in

:    in 3.1.0. Use [[\craft\services\ProjectConfig]] instead.



System Settings service.

An instance of the System Settings service is globally accessible in Craft via [`Craft::$app->systemSettings`](craft-base-applicationtrait.md#method-getsystemsettings).



[View source](https://github.com/craftcms/cms/blob/master/src/services/SystemSettings.php)


## Public Properties

| Property                                                                                                                   | Description
| -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component") | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [defaults](craft-services-systemsettings.md#defaults)                                                                      | [array](http://php.net/language.types.array)
| [emailSettings](craft-services-systemsettings.md#emailsettings)                                                            | [craft\models\MailSettings](craft-models-mailsettings.md)

### `defaults`

::: danger DEPRECATED
Deprecated in 3.1.0
:::


Type

:   [array](http://php.net/language.types.array)







[View source](https://github.com/craftcms/cms/blob/master/src/services/SystemSettings.php#L29)



### `emailSettings`



Type

:   [craft\models\MailSettings](craft-models-mailsettings.md)

Access

:   Read-only







[View source](https://github.com/craftcms/cms/blob/master/src/services/SystemSettings.php)







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
| [getEmailSettings()](craft-services-systemsettings.md#method-getemailsettings)                                                              | Returns the email settings.
| [getSetting()](craft-services-systemsettings.md#method-getsetting)                                                                          | Returns an individual system setting.
| [getSettings()](craft-services-systemsettings.md#method-getsettings)                                                                        | Returns the system settings for a category.
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component") | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")             | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")         | Returns a value indicating whether a property is defined.
| [init()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#init()-detail "Defined by yii\base\BaseObject")                       | Initializes the object.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                           | Detaches an existing event handler from this component.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                             | Attaches an event handler to an event.
| [saveSettings()](craft-services-systemsettings.md#method-savesettings)                                                                      | Saves the system settings for a category.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                   | Triggers an event.

### `getEmailSettings()`

::: danger DEPRECATED
Deprecated in 3.1.0. Use [craft\helpers\App::mailSettings()](craft-helpers-app.md#method-mailsettings) instead.
:::




Returns the email settings.




[View source](https://github.com/craftcms/cms/blob/master/src/services/SystemSettings.php#L76-L79)



#### Returns

[craft\models\MailSettings](craft-models-mailsettings.md)



### `getSetting()`

::: danger DEPRECATED
Deprecated in 3.1.0. Use [craft\services\ProjectConfig::get()](craft-services-projectconfig.md#method-get) instead.
:::




Returns an individual system setting.




[View source](https://github.com/craftcms/cms/blob/master/src/services/SystemSettings.php#L51-L54)


#### Arguments

- `$category` ([string](http://php.net/language.types.string))
- `$key` ([string](http://php.net/language.types.string))

#### Returns

`mixed`



### `getSettings()`

::: danger DEPRECATED
Deprecated in 3.1.0. Use [craft\services\ProjectConfig::get()](craft-services-projectconfig.md#method-get) instead.
:::




Returns the system settings for a category.




[View source](https://github.com/craftcms/cms/blob/master/src/services/SystemSettings.php#L38-L41)


#### Arguments

- `$category` ([string](http://php.net/language.types.string))

#### Returns

[array](http://php.net/language.types.array)



### `saveSettings()`

::: danger DEPRECATED
Deprecated in 3.1.0. Use [craft\services\ProjectConfig::set()](craft-services-projectconfig.md#method-set) instead.
:::




Saves the system settings for a category.




[View source](https://github.com/craftcms/cms/blob/master/src/services/SystemSettings.php#L64-L68)


#### Arguments

- `$category` ([string](http://php.net/language.types.string))
- `$settings` ([array](http://php.net/language.types.array), [null](http://php.net/language.types.null))

#### Returns

[boolean](http://php.net/language.types.boolean) – Whether the new settings saved









