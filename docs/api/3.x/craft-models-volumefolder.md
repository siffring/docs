---
title: craft\models\VolumeFolder
code:
  - php
  - twig
---

# VolumeFolder

Type

:   Class

Namespace

:   craft\models

Inherits

:   [craft\models\VolumeFolder](craft-models-volumefolder.md) &raquo;
[craft\base\Model](craft-base-model.md) &raquo;
[yii\base\Model](https://www.yiiframework.com/doc/api/2.0/yii-base-model) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [ArrayAccess](http://php.net/class.arrayaccess), [IteratorAggregate](http://php.net/class.iteratoraggregate), [yii\base\Arrayable](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayable), [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable), [yii\base\StaticInstanceInterface](https://www.yiiframework.com/doc/api/2.0/yii-base-staticinstanceinterface)

Uses traits

:   [craft\base\ClonefixTrait](craft-base-clonefixtrait.md), [yii\base\ArrayableTrait](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait), [yii\base\StaticInstanceTrait](https://www.yiiframework.com/doc/api/2.0/yii-base-staticinstancetrait)

Since

:   3.0.0



The VolumeFolder model class.





[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php)


## Public Properties

| Property                                                                                                                         | Description
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [activeValidators](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$activeValidators-detail "Defined by yii\base\Model") | [yii\validators\Validator](https://www.yiiframework.com/doc/api/2.0/yii-validators-validator) – The validators applicable to the current [scenario](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$scenario-detail).
| [attributes](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$attributes-detail "Defined by yii\base\Model")             | [array](http://php.net/language.types.array) – Attribute values (name => value).
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component")       | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [children](craft-models-volumefolder.md#children)                                                                                | [craft\models\VolumeFolder](craft-models-volumefolder.md)[]
| [errors](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$errors-detail "Defined by yii\base\Model")                     | [array](http://php.net/language.types.array) – Errors for all attributes or the specified attribute.
| [firstErrors](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$firstErrors-detail "Defined by yii\base\Model")           | [array](http://php.net/language.types.array) – The first errors.
| [id](craft-models-volumefolder.md#id)                                                                                            | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – ID
| [iterator](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$iterator-detail "Defined by yii\base\Model")                 | [ArrayIterator](http://php.net/class.arrayiterator) – An iterator for traversing the items in the list.
| [name](craft-models-volumefolder.md#name)                                                                                        | [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – Name
| [parent](craft-models-volumefolder.md#parent)                                                                                    | [craft\models\VolumeFolder](craft-models-volumefolder.md), [null](http://php.net/language.types.null)
| [parentId](craft-models-volumefolder.md#parentid)                                                                                | [integer](http://php.net/language.types.integer), [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – Parent ID
| [path](craft-models-volumefolder.md#path)                                                                                        | [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – Path
| [scenario](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$scenario-detail "Defined by yii\base\Model")                 | [string](http://php.net/language.types.string) – The scenario that this model is in.
| [uid](craft-models-volumefolder.md#uid)                                                                                          | [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – UID
| [validators](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$validators-detail "Defined by yii\base\Model")             | [ArrayObject](http://php.net/class.arrayobject), [yii\validators\Validator](https://www.yiiframework.com/doc/api/2.0/yii-validators-validator) – All the validators declared in the model.
| [volume](craft-models-volumefolder.md#volume)                                                                                    | [craft\base\VolumeInterface](craft-base-volumeinterface.md)
| [volumeId](craft-models-volumefolder.md#volumeid)                                                                                | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – Volume ID

### `children`



Type

:   [craft\models\VolumeFolder](craft-models-volumefolder.md)[]







[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php)



### `id`



Type

:   [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null)



ID



[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L27)



### `name`



Type

:   [string](http://php.net/language.types.string), [null](http://php.net/language.types.null)



Name



[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L42)



### `parent`



Type

:   [craft\models\VolumeFolder](craft-models-volumefolder.md), [null](http://php.net/language.types.null)

Access

:   Read-only







[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php)



### `parentId`



Type

:   [integer](http://php.net/language.types.integer), [string](http://php.net/language.types.string), [null](http://php.net/language.types.null)



Parent ID



[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L32)



### `path`



Type

:   [string](http://php.net/language.types.string), [null](http://php.net/language.types.null)



Path



[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L47)



### `uid`



Type

:   [string](http://php.net/language.types.string), [null](http://php.net/language.types.null)



UID



[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L52)



### `volume`



Type

:   [craft\base\VolumeInterface](craft-base-volumeinterface.md)

Access

:   Read-only







[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php)



### `volumeId`



Type

:   [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null)



Volume ID



[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L37)







## Public Methods

| Method                                                                                                                                          | Description
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__call()-detail "Defined by yii\base\BaseObject")                       | Calls the named method which is not a class method.
| [__clone()](craft-base-clonefixtrait.md#method-clone "Defined by craft\base\ClonefixTrait")                                                     |
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")             | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__get()-detail "Defined by yii\base\BaseObject")                         | Returns the value of an object property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__isset()-detail "Defined by yii\base\BaseObject")                     | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__set()-detail "Defined by yii\base\BaseObject")                         | Sets value of an object property.
| [__toString()](craft-models-volumefolder.md#method-tostring)                                                                                    | Use the folder name as the string representation.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__unset()-detail "Defined by yii\base\BaseObject")                     | Sets an object property to null.
| [activeAttributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#activeAttributes()-detail "Defined by yii\base\Model")             | Returns the attribute names that are subject to validation in the current scenario.
| [addChild()](craft-models-volumefolder.md#method-addchild)                                                                                      | Add a child folder manually.
| [addError()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#addError()-detail "Defined by yii\base\Model")                             | Adds a new error to the specified attribute.
| [addErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#addErrors()-detail "Defined by yii\base\Model")                           | Adds a list of errors.
| [addModelErrors()](craft-base-model.md#method-addmodelerrors "Defined by craft\base\Model")                                                     | Adds errors from another model, with a given attribute name prefix.
| [afterValidate()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#afterValidate()-detail "Defined by yii\base\Model")                   | This method is invoked after validation ends.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")         | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")       | Attaches a list of behaviors to the component.
| [attributeHints()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#attributeHints()-detail "Defined by yii\base\Model")                 | Returns the attribute hints.
| [attributeLabels()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#attributeLabels()-detail "Defined by yii\base\Model")               | Returns the attribute labels.
| [attributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#attributes()-detail "Defined by yii\base\Model")                         | Returns the list of attribute names.
| [beforeValidate()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#beforeValidate()-detail "Defined by yii\base\Model")                 | This method is invoked before validation starts.
| [behaviors()](craft-base-model.md#method-behaviors "Defined by craft\base\Model")                                                               | Returns a list of behaviors that this component should behave as.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canGetProperty()-detail "Defined by yii\base\BaseObject")       | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canSetProperty()-detail "Defined by yii\base\BaseObject")       | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                 | Returns the fully qualified name of this class.
| [clearErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#clearErrors()-detail "Defined by yii\base\Model")                       | Removes errors for all attributes or a single attribute.
| [createValidators()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#createValidators()-detail "Defined by yii\base\Model")             | Creates validator objects based on the validation rules specified in [rules()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#rules()-detail).
| [datetimeAttributes()](craft-base-model.md#method-datetimeattributes "Defined by craft\base\Model")                                             | Returns the names of any attributes that should hold [DateTime](http://php.net/class.datetime) values.
| [detachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehavior()-detail "Defined by yii\base\Component")         | Detaches a behavior from the component.
| [detachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehaviors()-detail "Defined by yii\base\Component")       | Detaches all behaviors from the component.
| [ensureBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#ensureBehaviors()-detail "Defined by yii\base\Component")       | Makes sure that the behaviors declared in [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail) are attached to this component.
| [extraFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extraFields()-detail "Defined by yii\base\ArrayableTrait")     | Returns the list of fields that can be expanded further and returned by [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail).
| [fields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#fields()-detail "Defined by yii\base\ArrayableTrait")               | Returns the list of fields that should be returned by default by [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail) when no specific fields are specified.
| [formName()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#formName()-detail "Defined by yii\base\Model")                             | Returns the form name that this model class should use.
| [generateAttributeLabel()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#generateAttributeLabel()-detail "Defined by yii\base\Model") | Generates a user friendly attribute label based on the give attribute name.
| [getActiveValidators()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getActiveValidators()-detail "Defined by yii\base\Model")       | Returns the validators applicable to the current [scenario](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$scenario-detail).
| [getAttributeHint()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getAttributeHint()-detail "Defined by yii\base\Model")             | Returns the text hint for the specified attribute.
| [getAttributeLabel()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getAttributeLabel()-detail "Defined by yii\base\Model")           | Returns the text label for the specified attribute.
| [getAttributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getAttributes()-detail "Defined by yii\base\Model")                   | Returns attribute values.
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")               | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")             | Returns all behaviors attached to this component.
| [getChildren()](craft-models-volumefolder.md#method-getchildren)                                                                                | Get this folder's children.
| [getError()](craft-base-model.md#method-geterror "Defined by craft\base\Model")                                                                 | Returns the first error of the specified attribute.
| [getErrorSummary()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getErrorSummary()-detail "Defined by yii\base\Model")               | Returns the errors for all attributes as a one-dimensional array.
| [getErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getErrors()-detail "Defined by yii\base\Model")                           | Returns the errors for all attributes or a single attribute.
| [getFirstError()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getFirstError()-detail "Defined by yii\base\Model")                   | Returns the first error of the specified attribute.
| [getFirstErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getFirstErrors()-detail "Defined by yii\base\Model")                 | Returns the first error of every attribute in the model.
| [getIterator()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getIterator()-detail "Defined by yii\base\Model")                       | Returns an iterator for traversing the attributes in the model.
| [getParent()](craft-models-volumefolder.md#method-getparent)                                                                                    |
| [getScenario()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getScenario()-detail "Defined by yii\base\Model")                       | Returns the scenario that this model is used in.
| [getValidators()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getValidators()-detail "Defined by yii\base\Model")                   | Returns all the validators declared in [rules()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#rules()-detail).
| [getVolume()](craft-models-volumefolder.md#method-getvolume)                                                                                    |
| [hasErrors()](craft-base-model.md#method-haserrors "Defined by craft\base\Model")                                                               | Returns a value indicating whether there is any validation error.
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component")     | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")                 | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")             | Returns a value indicating whether a property is defined.
| [init()](craft-base-model.md#method-init "Defined by craft\base\Model")                                                                         | Initializes the object.
| [instance()](https://www.yiiframework.com/doc/api/2.0/yii-base-staticinstancetrait#instance()-detail "Defined by yii\base\StaticInstanceTrait") | Returns static class instance, which can be used to obtain meta information.
| [isAttributeActive()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#isAttributeActive()-detail "Defined by yii\base\Model")           | Returns a value indicating whether the attribute is active in the current scenario.
| [isAttributeRequired()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#isAttributeRequired()-detail "Defined by yii\base\Model")       | Returns a value indicating whether the attribute is required.
| [isAttributeSafe()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#isAttributeSafe()-detail "Defined by yii\base\Model")               | Returns a value indicating whether the attribute is safe for massive assignments.
| [load()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#load()-detail "Defined by yii\base\Model")                                     | Populates the model with input data.
| [loadMultiple()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#loadMultiple()-detail "Defined by yii\base\Model")                     | Populates a set of models with the data from end user.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                               | Detaches an existing event handler from this component.
| [offsetExists()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetExists()-detail "Defined by yii\base\Model")                     | Returns whether there is an element at the specified offset.
| [offsetGet()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetGet()-detail "Defined by yii\base\Model")                           | Returns the element at the specified offset.
| [offsetSet()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetSet()-detail "Defined by yii\base\Model")                           | Sets the element at the specified offset.
| [offsetUnset()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetUnset()-detail "Defined by yii\base\Model")                       | Sets the element value at the specified offset to null.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                                 | Attaches an event handler to an event.
| [onUnsafeAttribute()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#onUnsafeAttribute()-detail "Defined by yii\base\Model")           | This method is invoked when an unsafe attribute is being massively assigned.
| [rules()](craft-base-model.md#method-rules "Defined by craft\base\Model")                                                                       | Returns the validation rules for attributes.
| [safeAttributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#safeAttributes()-detail "Defined by yii\base\Model")                 | Returns the attribute names that are safe to be massively assigned in the current scenario.
| [scenarios()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#scenarios()-detail "Defined by yii\base\Model")                           | Returns a list of scenarios and the corresponding active attributes.
| [setAttributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#setAttributes()-detail "Defined by yii\base\Model")                   | Sets the attribute values in a massive way.
| [setChildren()](craft-models-volumefolder.md#method-setchildren)                                                                                | Set the child folders.
| [setScenario()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#setScenario()-detail "Defined by yii\base\Model")                       | Sets the scenario for the model.
| [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail "Defined by yii\base\ArrayableTrait")             | Converts the model into an array.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                       | Triggers an event.
| [validate()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#validate()-detail "Defined by yii\base\Model")                             | Performs the data validation.
| [validateMultiple()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#validateMultiple()-detail "Defined by yii\base\Model")             | Validates multiple models.

### `__toString()`





Use the folder name as the string representation.




[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L74-L77)



#### Returns

[string](http://php.net/language.types.string)



### `addChild()`





Add a child folder manually.




[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L137-L144)


#### Arguments

- `$folder` ([craft\models\VolumeFolder](craft-models-volumefolder.md))




### `getChildren()`





Get this folder's children.




[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L111-L118)



#### Returns

[craft\models\VolumeFolder](craft-models-volumefolder.md)[]



### `getParent()`










[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L123-L130)



#### Returns

[craft\models\VolumeFolder](craft-models-volumefolder.md), [null](http://php.net/language.types.null)



### `getVolume()`










[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L83-L94)



#### Returns

[craft\base\VolumeInterface](craft-base-volumeinterface.md)

#### Throws

- [yii\base\InvalidConfigException](https://www.yiiframework.com/doc/api/2.0/yii-base-invalidconfigexception)\
  if [volumeId](craft-models-volumefolder.md#volumeid) is invalid


### `setChildren()`





Set the child folders.




[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L101-L104)


#### Arguments

- `$children` ([craft\models\VolumeFolder](craft-models-volumefolder.md)[])






## Protected Methods

| Method                                                                                                                                                  | Description
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [defineRules()](craft-models-volumefolder.md#method-definerules)                                                                                        | Returns the validation rules for attributes.
| [extractFieldsFor()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extractFieldsFor()-detail "Defined by yii\base\ArrayableTrait")   | Extract nested fields from a fields collection for a given root field Nested fields are separated with dots (.). e.g: "item.id" The previous example would extract "id".
| [extractRootFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extractRootFields()-detail "Defined by yii\base\ArrayableTrait") | Extracts the root field names from nested fields.
| [resolveFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#resolveFields()-detail "Defined by yii\base\ArrayableTrait")         | Determines which fields can be returned by [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail).

### `defineRules()`



Since

:   3.4.0



Returns the validation rules for attributes.



See [rules()](craft-base-model.md#method-rules) for details about what should be returned.

Models should override this method instead of [rules()](craft-base-model.md#method-rules) so [EVENT_DEFINE_RULES](craft-base-model.md#event-define-rules) handlers can modify the
class-defined rules.




[View source](https://github.com/craftcms/cms/blob/master/src/models/VolumeFolder.php#L62-L67)



#### Returns

[array](http://php.net/language.types.array)





## Constants

| Constant           | Description
| ------------------ | ---------------------------------
| `SCENARIO_DEFAULT` | The name of the default scenario.


