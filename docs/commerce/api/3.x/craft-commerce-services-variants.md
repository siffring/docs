---
title: craft\commerce\services\Variants
code:
  - php
  - twig
---

# Variants

Type

:   Class

Namespace

:   craft\commerce\services

Inherits

:   [craft\commerce\services\Variants](craft-commerce-services-variants.md) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable)

Since

:   2.0



Variant service.





[View source](https://github.com/craftcms/commerce/blob/master/src/services/Variants.php)


## Public Properties

| Property                                                                                                                   | Description
| -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component") | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [variantGqlContentArguments](craft-commerce-services-variants.md#variantgqlcontentarguments)                               | [array](http://php.net/language.types.array)

### `variantGqlContentArguments`



Type

:   [array](http://php.net/language.types.array)

Access

:   Read-only

Since

:   3.1.4







[View source](https://github.com/craftcms/commerce/blob/master/src/services/Variants.php)







## Public Methods

| Method                                                                                                                                      | Description
| ------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__call()-detail "Defined by yii\base\Component")                     | Calls the named method which is not a class method.
| [__clone()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__clone()-detail "Defined by yii\base\Component")                   | This method is called after the object is created by cloning an existing one.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")         | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__get()-detail "Defined by yii\base\Component")                       | Returns the value of a component property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__isset()-detail "Defined by yii\base\Component")                   | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__set()-detail "Defined by yii\base\Component")                       | Sets the value of a component property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__unset()-detail "Defined by yii\base\Component")                   | Sets a component property to be null.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")     | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")   | Attaches a list of behaviors to the component.
| [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail "Defined by yii\base\Component")               | Returns a list of behaviors that this component should behave as.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canGetProperty()-detail "Defined by yii\base\Component")     | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canSetProperty()-detail "Defined by yii\base\Component")     | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")             | Returns the fully qualified name of this class.
| [detachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehavior()-detail "Defined by yii\base\Component")     | Detaches a behavior from the component.
| [detachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehaviors()-detail "Defined by yii\base\Component")   | Detaches all behaviors from the component.
| [ensureBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#ensureBehaviors()-detail "Defined by yii\base\Component")   | Makes sure that the behaviors declared in [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail) are attached to this component.
| [getAllVariantsByProductId()](craft-commerce-services-variants.md#method-getallvariantsbyproductid)                                         | Returns a product's variants, per the product's ID.
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")           | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")         | Returns all behaviors attached to this component.
| [getVariantById()](craft-commerce-services-variants.md#method-getvariantbyid)                                                               | Returns a variant by its ID.
| [getVariantGqlContentArguments()](craft-commerce-services-variants.md#method-getvariantgqlcontentarguments)                                 |
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component") | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasMethod()-detail "Defined by yii\base\Component")               | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasProperty()-detail "Defined by yii\base\Component")           | Returns a value indicating whether a property is defined for this component.
| [init()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#init()-detail "Defined by yii\base\BaseObject")                       | Initializes the object.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                           | Detaches an existing event handler from this component.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                             | Attaches an event handler to an event.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                   | Triggers an event.

### `getAllVariantsByProductId()`





Returns a product's variants, per the product's ID.




[View source](https://github.com/craftcms/commerce/blob/master/src/services/Variants.php#L40-L49)


#### Arguments

- `$productId` ([integer](http://php.net/language.types.integer)) – Product ID
- `$siteId` ([integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null)) – Site ID for which to return the variants. Defaults to `null` which is current site.

#### Returns

[craft\commerce\elements\Variant](craft-commerce-elements-variant.md)[]



### `getVariantById()`





Returns a variant by its ID.




[View source](https://github.com/craftcms/commerce/blob/master/src/services/Variants.php#L58-L67)


#### Arguments

- `$variantId` ([integer](http://php.net/language.types.integer)) – The variant’s ID.
- `$siteId` ([integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null)) – The site ID for which to fetch the variant. Defaults to `null` which is current site.

#### Returns

[craft\commerce\elements\Variant](craft-commerce-elements-variant.md), [null](http://php.net/language.types.null)



### `getVariantGqlContentArguments()`



Since

:   3.1.4








[View source](https://github.com/craftcms/commerce/blob/master/src/services/Variants.php#L73-L102)



#### Returns

[array](http://php.net/language.types.array)









