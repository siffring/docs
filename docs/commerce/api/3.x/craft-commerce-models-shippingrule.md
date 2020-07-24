---
title: craft\commerce\models\ShippingRule
code:
  - php
  - twig
---

# ShippingRule

Type

:   Class

Namespace

:   craft\commerce\models

Inherits

:   [craft\commerce\models\ShippingRule](craft-commerce-models-shippingrule.md) &raquo;
[craft\commerce\base\Model](craft-commerce-base-model.md) &raquo;
[craft\base\Model](https://docs.craftcms.com/api/v3/craft-base-model.html) &raquo;
[yii\base\Model](https://www.yiiframework.com/doc/api/2.0/yii-base-model) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [ArrayAccess](http://php.net/class.arrayaccess), [IteratorAggregate](http://php.net/class.iteratoraggregate), [craft\commerce\base\ShippingRuleInterface](craft-commerce-base-shippingruleinterface.md), [yii\base\Arrayable](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayable), [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable), [yii\base\StaticInstanceInterface](https://www.yiiframework.com/doc/api/2.0/yii-base-staticinstanceinterface)

Uses traits

:   [craft\base\ClonefixTrait](https://docs.craftcms.com/api/v3/craft-base-clonefixtrait.html), [yii\base\ArrayableTrait](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait), [yii\base\StaticInstanceTrait](https://www.yiiframework.com/doc/api/2.0/yii-base-staticinstancetrait)

Since

:   2.0



Shipping rule model





[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php)


## Public Properties

| Property                                                                                                                         | Description
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [activeValidators](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$activeValidators-detail "Defined by yii\base\Model") | [yii\validators\Validator](https://www.yiiframework.com/doc/api/2.0/yii-validators-validator) – The validators applicable to the current [scenario](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$scenario-detail).
| [attributes](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$attributes-detail "Defined by yii\base\Model")             | [array](http://php.net/language.types.array) – Attribute values (name => value).
| [baseRate](craft-commerce-models-shippingrule.md#baserate)                                                                       | [float](http://php.net/language.types.float) – Base rate
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component")       | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [description](craft-commerce-models-shippingrule.md#description)                                                                 | [string](http://php.net/language.types.string) – Description
| [enabled](craft-commerce-models-shippingrule.md#enabled)                                                                         | [boolean](http://php.net/language.types.boolean) – Enabled
| [errors](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$errors-detail "Defined by yii\base\Model")                     | [array](http://php.net/language.types.array) – Errors for all attributes or the specified attribute.
| [firstErrors](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$firstErrors-detail "Defined by yii\base\Model")           | [array](http://php.net/language.types.array) – The first errors.
| [id](craft-commerce-models-shippingrule.md#id)                                                                                   | [integer](http://php.net/language.types.integer) – ID
| [isEnabled](craft-commerce-models-shippingrule.md#isenabled)                                                                     | [boolean](http://php.net/language.types.boolean)
| [isLite](craft-commerce-models-shippingrule.md#islite)                                                                           | [boolean](http://php.net/language.types.boolean) – Is lite shipping rule
| [iterator](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$iterator-detail "Defined by yii\base\Model")                 | [ArrayIterator](http://php.net/class.arrayiterator) – An iterator for traversing the items in the list.
| [maxQty](craft-commerce-models-shippingrule.md#maxqty)                                                                           | [integer](http://php.net/language.types.integer) – Maximum Quantity
| [maxRate](craft-commerce-models-shippingrule.md#maxrate)                                                                         | [float](http://php.net/language.types.float) – Maximum rate
| [maxTotal](craft-commerce-models-shippingrule.md#maxtotal)                                                                       | [float](http://php.net/language.types.float) – Maximum total
| [maxWeight](craft-commerce-models-shippingrule.md#maxweight)                                                                     | [float](http://php.net/language.types.float) – Maximum Weight
| [methodId](craft-commerce-models-shippingrule.md#methodid)                                                                       | [integer](http://php.net/language.types.integer) – Shipping method ID
| [minQty](craft-commerce-models-shippingrule.md#minqty)                                                                           | [integer](http://php.net/language.types.integer) – Minimum Quantity
| [minRate](craft-commerce-models-shippingrule.md#minrate)                                                                         | [float](http://php.net/language.types.float) – Minimum Rate
| [minTotal](craft-commerce-models-shippingrule.md#mintotal)                                                                       | [float](http://php.net/language.types.float) – Minimum total
| [minWeight](craft-commerce-models-shippingrule.md#minweight)                                                                     | [float](http://php.net/language.types.float) – Minimum Weight
| [name](craft-commerce-models-shippingrule.md#name)                                                                               | [string](http://php.net/language.types.string) – Name
| [options](craft-commerce-models-shippingrule.md#options)                                                                         | `mixed`
| [perItemRate](craft-commerce-models-shippingrule.md#peritemrate)                                                                 | [float](http://php.net/language.types.float) – Per item rate
| [percentageRate](craft-commerce-models-shippingrule.md#percentagerate)                                                           | [float](http://php.net/language.types.float) – Percentage rate
| [priority](craft-commerce-models-shippingrule.md#priority)                                                                       | [integer](http://php.net/language.types.integer) – Priority
| [scenario](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$scenario-detail "Defined by yii\base\Model")                 | [string](http://php.net/language.types.string) – The scenario that this model is in.
| [shippingRuleCategories](craft-commerce-models-shippingrule.md#shippingrulecategories)                                           | [craft\commerce\models\ShippingRuleCategory](craft-commerce-models-shippingrulecategory.md)[]
| [shippingZone](craft-commerce-models-shippingrule.md#shippingzone)                                                               | `mixed`
| [shippingZoneId](craft-commerce-models-shippingrule.md#shippingzoneid)                                                           | [integer](http://php.net/language.types.integer) – Shipping zone ID
| [validators](https://www.yiiframework.com/doc/api/2.0/yii-base-model#$validators-detail "Defined by yii\base\Model")             | [ArrayObject](http://php.net/class.arrayobject), [yii\validators\Validator](https://www.yiiframework.com/doc/api/2.0/yii-validators-validator) – All the validators declared in the model.
| [weightRate](craft-commerce-models-shippingrule.md#weightrate)                                                                   | [float](http://php.net/language.types.float) – Weight rate

### `baseRate`



Type

:   [float](http://php.net/language.types.float)



Base rate



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L96)



### `description`



Type

:   [string](http://php.net/language.types.string)



Description



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L41)



### `enabled`



Type

:   [boolean](http://php.net/language.types.boolean)



Enabled



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L61)



### `id`



Type

:   [integer](http://php.net/language.types.integer)



ID



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L31)



### `isEnabled`



Type

:   [boolean](http://php.net/language.types.boolean)

Access

:   Read-only







[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php)



### `isLite`



Type

:   [boolean](http://php.net/language.types.boolean)



Is lite shipping rule



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L126)



### `maxQty`



Type

:   [integer](http://php.net/language.types.integer)



Maximum Quantity



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L71)



### `maxRate`



Type

:   [float](http://php.net/language.types.float)



Maximum rate



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L121)



### `maxTotal`



Type

:   [float](http://php.net/language.types.float)



Maximum total



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L81)



### `maxWeight`



Type

:   [float](http://php.net/language.types.float)



Maximum Weight



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L91)



### `methodId`



Type

:   [integer](http://php.net/language.types.integer)



Shipping method ID



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L51)



### `minQty`



Type

:   [integer](http://php.net/language.types.integer)



Minimum Quantity



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L66)



### `minRate`



Type

:   [float](http://php.net/language.types.float)



Minimum Rate



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L116)



### `minTotal`



Type

:   [float](http://php.net/language.types.float)



Minimum total



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L76)



### `minWeight`



Type

:   [float](http://php.net/language.types.float)



Minimum Weight



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L86)



### `name`



Type

:   [string](http://php.net/language.types.string)



Name



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L36)



### `options`



Type

:   `mixed`

Access

:   Read-only







[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php)



### `perItemRate`



Type

:   [float](http://php.net/language.types.float)



Per item rate



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L101)



### `percentageRate`



Type

:   [float](http://php.net/language.types.float)



Percentage rate



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L106)



### `priority`



Type

:   [integer](http://php.net/language.types.integer)



Priority



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L56)



### `shippingRuleCategories`



Type

:   [craft\commerce\models\ShippingRuleCategory](craft-commerce-models-shippingrulecategory.md)[]







[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php)



### `shippingZone`



Type

:   `mixed`

Access

:   Read-only







[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php)



### `shippingZoneId`



Type

:   [integer](http://php.net/language.types.integer)



Shipping zone ID



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L46)



### `weightRate`



Type

:   [float](http://php.net/language.types.float)



Weight rate



[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L111)







## Public Methods

| Method                                                                                                                                          | Description
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__call()-detail "Defined by yii\base\Component")                         | Calls the named method which is not a class method.
| [__clone()](https://docs.craftcms.com/api/v3/craft-base-clonefixtrait.html#method-__clone "Defined by craft\base\ClonefixTrait")                |
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")             | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__get()-detail "Defined by yii\base\Component")                           | Returns the value of a component property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__isset()-detail "Defined by yii\base\Component")                       | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__set()-detail "Defined by yii\base\Component")                           | Sets the value of a component property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__unset()-detail "Defined by yii\base\Component")                       | Sets a component property to be null.
| [activeAttributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#activeAttributes()-detail "Defined by yii\base\Model")             | Returns the attribute names that are subject to validation in the current scenario.
| [addError()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#addError()-detail "Defined by yii\base\Model")                             | Adds a new error to the specified attribute.
| [addErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#addErrors()-detail "Defined by yii\base\Model")                           | Adds a list of errors.
| [addModelErrors()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-addmodelerrors "Defined by craft\base\Model")                  | Adds errors from another model, with a given attribute name prefix.
| [afterValidate()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#afterValidate()-detail "Defined by yii\base\Model")                   | This method is invoked after validation ends.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")         | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")       | Attaches a list of behaviors to the component.
| [attributeHints()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#attributeHints()-detail "Defined by yii\base\Model")                 | Returns the attribute hints.
| [attributeLabels()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#attributeLabels()-detail "Defined by yii\base\Model")               | Returns the attribute labels.
| [attributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#attributes()-detail "Defined by yii\base\Model")                         | Returns the list of attribute names.
| [beforeValidate()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#beforeValidate()-detail "Defined by yii\base\Model")                 | This method is invoked before validation starts.
| [behaviors()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-behaviors "Defined by craft\base\Model")                            | Returns a list of behaviors that this component should behave as.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canGetProperty()-detail "Defined by yii\base\Component")         | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canSetProperty()-detail "Defined by yii\base\Component")         | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                 | Returns the fully qualified name of this class.
| [clearErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#clearErrors()-detail "Defined by yii\base\Model")                       | Removes errors for all attributes or a single attribute.
| [createValidators()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#createValidators()-detail "Defined by yii\base\Model")             | Creates validator objects based on the validation rules specified in [rules()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#rules()-detail).
| [datetimeAttributes()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-datetimeattributes "Defined by craft\base\Model")          | Returns the names of any attributes that should hold [DateTime](http://php.net/class.datetime) values.
| [defineRules()](craft-commerce-models-shippingrule.md#method-definerules)                                                                       | Returns the validation rules for attributes.
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
| [getBaseRate()](craft-commerce-models-shippingrule.md#method-getbaserate)                                                                       | Returns a base shipping cost. This is added at the order level.
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")               | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")             | Returns all behaviors attached to this component.
| [getDescription()](craft-commerce-models-shippingrule.md#method-getdescription)                                                                 | Returns a description of the rates applied by this rule; Zero will not make any changes.
| [getError()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-geterror "Defined by craft\base\Model")                              | Returns the first error of the specified attribute.
| [getErrorSummary()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getErrorSummary()-detail "Defined by yii\base\Model")               | Returns the errors for all attributes as a one-dimensional array.
| [getErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getErrors()-detail "Defined by yii\base\Model")                           | Returns the errors for all attributes or a single attribute.
| [getFirstError()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getFirstError()-detail "Defined by yii\base\Model")                   | Returns the first error of the specified attribute.
| [getFirstErrors()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getFirstErrors()-detail "Defined by yii\base\Model")                 | Returns the first error of every attribute in the model.
| [getIsEnabled()](craft-commerce-models-shippingrule.md#method-getisenabled)                                                                     | Returns whether this shipping rule is enabled for listing and selection.
| [getIterator()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getIterator()-detail "Defined by yii\base\Model")                       | Returns an iterator for traversing the attributes in the model.
| [getMaxRate()](craft-commerce-models-shippingrule.md#method-getmaxrate)                                                                         |
| [getMinRate()](craft-commerce-models-shippingrule.md#method-getminrate)                                                                         | Returns a min cost this rule should have applied.
| [getOptions()](craft-commerce-models-shippingrule.md#method-getoptions)                                                                         | Returns this data as json on the order's shipping adjustment.
| [getPerItemRate()](craft-commerce-models-shippingrule.md#method-getperitemrate)                                                                 | Returns the flat rate that is multiplied per qty.
| [getPercentageRate()](craft-commerce-models-shippingrule.md#method-getpercentagerate)                                                           | Returns the percentage rate that is multiplied per line item subtotal.
| [getScenario()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getScenario()-detail "Defined by yii\base\Model")                       | Returns the scenario that this model is used in.
| [getShippingRuleCategories()](craft-commerce-models-shippingrule.md#method-getshippingrulecategories)                                           |
| [getShippingZone()](craft-commerce-models-shippingrule.md#method-getshippingzone)                                                               |
| [getValidators()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#getValidators()-detail "Defined by yii\base\Model")                   | Returns all the validators declared in [rules()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#rules()-detail).
| [getWeightRate()](craft-commerce-models-shippingrule.md#method-getweightrate)                                                                   | Returns the rate that is multiplied by the line item's weight.
| [hasErrors()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-haserrors "Defined by craft\base\Model")                            | Returns a value indicating whether there is any validation error.
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component")     | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasMethod()-detail "Defined by yii\base\Component")                   | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasProperty()-detail "Defined by yii\base\Component")               | Returns a value indicating whether a property is defined for this component.
| [init()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-init "Defined by craft\base\Model")                                      | Initializes the object.
| [instance()](https://www.yiiframework.com/doc/api/2.0/yii-base-staticinstancetrait#instance()-detail "Defined by yii\base\StaticInstanceTrait") | Returns static class instance, which can be used to obtain meta information.
| [isAttributeActive()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#isAttributeActive()-detail "Defined by yii\base\Model")           | Returns a value indicating whether the attribute is active in the current scenario.
| [isAttributeRequired()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#isAttributeRequired()-detail "Defined by yii\base\Model")       | Returns a value indicating whether the attribute is required.
| [isAttributeSafe()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#isAttributeSafe()-detail "Defined by yii\base\Model")               | Returns a value indicating whether the attribute is safe for massive assignments.
| [load()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#load()-detail "Defined by yii\base\Model")                                     | Populates the model with input data.
| [loadMultiple()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#loadMultiple()-detail "Defined by yii\base\Model")                     | Populates a set of models with the data from end user.
| [matchOrder()](craft-commerce-models-shippingrule.md#method-matchorder)                                                                         | Returns whether this rule a match on the order. If false is returned, the shipping engine tries the next rule.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                               | Detaches an existing event handler from this component.
| [offsetExists()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetExists()-detail "Defined by yii\base\Model")                     | Returns whether there is an element at the specified offset.
| [offsetGet()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetGet()-detail "Defined by yii\base\Model")                           | Returns the element at the specified offset.
| [offsetSet()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetSet()-detail "Defined by yii\base\Model")                           | Sets the element at the specified offset.
| [offsetUnset()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#offsetUnset()-detail "Defined by yii\base\Model")                       | Sets the element value at the specified offset to null.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                                 | Attaches an event handler to an event.
| [onUnsafeAttribute()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#onUnsafeAttribute()-detail "Defined by yii\base\Model")           | This method is invoked when an unsafe attribute is being massively assigned.
| [rules()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-rules "Defined by craft\base\Model")                                    | Returns the validation rules for attributes.
| [safeAttributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#safeAttributes()-detail "Defined by yii\base\Model")                 | Returns the attribute names that are safe to be massively assigned in the current scenario.
| [scenarios()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#scenarios()-detail "Defined by yii\base\Model")                           | Returns a list of scenarios and the corresponding active attributes.
| [setAttributes()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#setAttributes()-detail "Defined by yii\base\Model")                   | Sets the attribute values in a massive way.
| [setScenario()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#setScenario()-detail "Defined by yii\base\Model")                       | Sets the scenario for the model.
| [setShippingRuleCategories()](craft-commerce-models-shippingrule.md#method-setshippingrulecategories)                                           |
| [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail "Defined by yii\base\ArrayableTrait")             | Converts the model into an array.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                       | Triggers an event.
| [validate()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#validate()-detail "Defined by yii\base\Model")                             | Performs the data validation.
| [validateMultiple()](https://www.yiiframework.com/doc/api/2.0/yii-base-model#validateMultiple()-detail "Defined by yii\base\Model")             | Validates multiple models.

### `defineRules()`





Returns the validation rules for attributes.



See [rules()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-rules) for details about what should be returned.

Models should override this method instead of [rules()](https://docs.craftcms.com/api/v3/craft-base-model.html#method-rules) so [EVENT_DEFINE_RULES](https://docs.craftcms.com/api/v3/craft-base-model.html#event-define-rules) handlers can modify the
class-defined rules.




[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L174-L200)



#### Returns

[array](http://php.net/language.types.array)



### `getBaseRate()`





Returns a base shipping cost. This is added at the order level.



Zero will not make any changes.




[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L360-L363)



#### Returns

[float](http://php.net/language.types.float)



### `getDescription()`





Returns a description of the rates applied by this rule;
Zero will not make any changes.








[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L383-L386)



#### Returns

[string](http://php.net/language.types.string)



### `getIsEnabled()`





Returns whether this shipping rule is enabled for listing and selection.








[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L205-L208)



#### Returns

[boolean](http://php.net/language.types.boolean)



### `getMaxRate()`










[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L367-L370)






### `getMinRate()`





Returns a min cost this rule should have applied.



If the total of your rates as applied to the order are less than this, the baseShippingCost
on the order is modified to meet this min rate.
Zero will not make any changes.




[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L375-L378)



#### Returns

[float](http://php.net/language.types.float)



### `getOptions()`





Returns this data as json on the order's shipping adjustment.








[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L328-L331)



#### Returns

`mixed`



### `getPerItemRate()`





Returns the flat rate that is multiplied per qty.



Zero will not make any changes.




[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L344-L347)


#### Arguments

- `$shippingCategoryId`

#### Returns

[float](http://php.net/language.types.float)



### `getPercentageRate()`





Returns the percentage rate that is multiplied per line item subtotal.



Zero will not make any changes.




[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L336-L339)


#### Arguments

- `$shippingCategoryId`

#### Returns

[float](http://php.net/language.types.float)



### `getShippingRuleCategories()`










[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L300-L307)



#### Returns

[craft\commerce\models\ShippingRuleCategory](craft-commerce-models-shippingrulecategory.md)[]



### `getShippingZone()`










[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L320-L323)



#### Returns

`mixed`



### `getWeightRate()`





Returns the rate that is multiplied by the line item's weight.



Zero will not make any changes.




[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L352-L355)


#### Arguments

- `$shippingCategoryId`

#### Returns

[float](http://php.net/language.types.float)



### `matchOrder()`





Returns whether this rule a match on the order. If false is returned, the shipping engine tries the next rule.








[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L213-L295)


#### Arguments

- `$order` ([craft\commerce\elements\Order](craft-commerce-elements-order.md))

#### Returns

[boolean](http://php.net/language.types.boolean)



### `setShippingRuleCategories()`










[View source](https://github.com/craftcms/commerce/blob/master/src/models/ShippingRule.php#L312-L315)


#### Arguments

- `$models` ([craft\commerce\models\ShippingRuleCategory](craft-commerce-models-shippingrulecategory.md)[])






## Protected Methods

| Method                                                                                                                                                  | Description
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [extractFieldsFor()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extractFieldsFor()-detail "Defined by yii\base\ArrayableTrait")   | Extract nested fields from a fields collection for a given root field Nested fields are separated with dots (.). e.g: "item.id" The previous example would extract "id".
| [extractRootFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extractRootFields()-detail "Defined by yii\base\ArrayableTrait") | Extracts the root field names from nested fields.
| [resolveFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#resolveFields()-detail "Defined by yii\base\ArrayableTrait")         | Determines which fields can be returned by [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail).



## Constants

| Constant           | Description
| ------------------ | ---------------------------------
| `SCENARIO_DEFAULT` | The name of the default scenario.


