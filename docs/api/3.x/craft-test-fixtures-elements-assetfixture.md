---
title: craft\test\fixtures\elements\AssetFixture
code:
  - php
  - twig
---

# AssetFixture

Type

:   Abstract Class

Namespace

:   craft\test\fixtures\elements

Inherits

:   [craft\test\fixtures\elements\AssetFixture](craft-test-fixtures-elements-assetfixture.md) &raquo;
[craft\test\fixtures\elements\ElementFixture](craft-test-fixtures-elements-elementfixture.md) &raquo;
[yii\test\ActiveFixture](https://www.yiiframework.com/doc/api/2.0/yii-test-activefixture) &raquo;
[yii\test\BaseActiveFixture](https://www.yiiframework.com/doc/api/2.0/yii-test-baseactivefixture) &raquo;
[yii\test\DbFixture](https://www.yiiframework.com/doc/api/2.0/yii-test-dbfixture) &raquo;
[yii\test\Fixture](https://www.yiiframework.com/doc/api/2.0/yii-test-fixture) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [ArrayAccess](http://php.net/class.arrayaccess), [Countable](http://php.net/class.countable), [IteratorAggregate](http://php.net/class.iteratoraggregate), [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable)

Uses traits

:   [yii\base\ArrayAccessTrait](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait), [yii\test\FileFixtureTrait](https://www.yiiframework.com/doc/api/2.0/yii-test-filefixturetrait)

Since

:   3.2



Class AssetFixture.

Credit to: https://github.com/robuust/craft-fixtures



[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php)


## Public Properties

| Property                                                                                                                                         | Description
| ------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component")                       | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [data](https://www.yiiframework.com/doc/api/2.0/yii-test-baseactivefixture#$data-detail "Defined by yii\test\BaseActiveFixture")                 | [array](http://php.net/language.types.array) – The data rows.
| [dataDirectory](https://www.yiiframework.com/doc/api/2.0/yii-test-filefixturetrait#$dataDirectory-detail "Defined by yii\test\FileFixtureTrait") | [string](http://php.net/language.types.string) – The directory path or [path alias](guide:concept-aliases) that contains the fixture data
| [dataFile](https://www.yiiframework.com/doc/api/2.0/yii-test-filefixturetrait#$dataFile-detail "Defined by yii\test\FileFixtureTrait")           | [string](http://php.net/language.types.string), [boolean](http://php.net/language.types.boolean) – The file path or [path alias](guide:concept-aliases) of the data file that contains the fixture data to be returned by `\yii\test\getData()`.
| [db](https://www.yiiframework.com/doc/api/2.0/yii-test-dbfixture#$db-detail "Defined by yii\test\DbFixture")                                     | [yii\db\Connection](https://www.yiiframework.com/doc/api/2.0/yii-db-connection), [array](http://php.net/language.types.array), [string](http://php.net/language.types.string) – The DB connection object or the application component ID of the DB connection.
| [depends](https://www.yiiframework.com/doc/api/2.0/yii-test-fixture#$depends-detail "Defined by yii\test\Fixture")                               | [array](http://php.net/language.types.array) – The fixtures that this fixture depends on.
| [element](craft-test-fixtures-elements-assetfixture.md#element)                                                                                  | [craft\base\Element](craft-base-element.md)
| [iterator](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait#$iterator-detail "Defined by yii\base\ArrayAccessTrait")           | [ArrayIterator](http://php.net/class.arrayiterator) – An iterator for traversing the cookies in the collection.
| [modelClass](craft-test-fixtures-elements-assetfixture.md#modelclass)                                                                            | [string](http://php.net/language.types.string) – The AR model class associated with this fixture.
| [tableName](https://www.yiiframework.com/doc/api/2.0/yii-test-activefixture#$tableName-detail "Defined by yii\test\ActiveFixture")               | [string](http://php.net/language.types.string) – The name of the database table that this fixture is about.
| [tableSchema](https://www.yiiframework.com/doc/api/2.0/yii-test-activefixture#$tableSchema-detail "Defined by yii\test\ActiveFixture")           | [yii\db\TableSchema](https://www.yiiframework.com/doc/api/2.0/yii-db-tableschema) – The schema information of the database table associated with this fixture.
| [unload](craft-test-fixtures-elements-elementfixture.md#unload "Defined by craft\test\fixtures\elements\ElementFixture")                         | [boolean](http://php.net/language.types.boolean) – Whether the fixture data should be unloaded

### `element`



Type

:   [craft\base\Element](craft-base-element.md)

Access

:   Read-only







[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php)



### `modelClass`



Type

:   [string](http://php.net/language.types.string)





The AR model class associated with this fixture.





[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L33)





## Protected Properties

| Property                                                                                                                   | Description
| -------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------
| [destinationAssetPath](craft-test-fixtures-elements-assetfixture.md#destinationassetpath)                                  | [string](http://php.net/language.types.string)
| [files](craft-test-fixtures-elements-assetfixture.md#files)                                                                | [array](http://php.net/language.types.array) – Used to track the files the fixture data file defines.
| [folderIds](craft-test-fixtures-elements-assetfixture.md#folderids)                                                        | [array](http://php.net/language.types.array)
| [siteIds](craft-test-fixtures-elements-elementfixture.md#siteids "Defined by craft\test\fixtures\elements\ElementFixture") | [array](http://php.net/language.types.array)
| [sourceAssetPath](craft-test-fixtures-elements-assetfixture.md#sourceassetpath)                                            | [string](http://php.net/language.types.string)
| [volumeIds](craft-test-fixtures-elements-assetfixture.md#volumeids)                                                        | [array](http://php.net/language.types.array)

### `destinationAssetPath`



Type

:   [string](http://php.net/language.types.string)







[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L58)



### `files`



Type

:   [array](http://php.net/language.types.array)



Used to track the files the fixture data file defines.



[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L48)



### `folderIds`



Type

:   [array](http://php.net/language.types.array)







[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L43)



### `sourceAssetPath`



Type

:   [string](http://php.net/language.types.string)







[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L53)



### `volumeIds`



Type

:   [array](http://php.net/language.types.array)







[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L38)





## Public Methods

| Method                                                                                                                                                        | Description
| ------------------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__call()-detail "Defined by yii\base\BaseObject")                                     | Calls the named method which is not a class method.
| [__clone()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__clone()-detail "Defined by yii\base\Component")                                     | This method is called after the object is created by cloning an existing one.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")                           | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__get()-detail "Defined by yii\base\BaseObject")                                       | Returns the value of an object property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__isset()-detail "Defined by yii\base\BaseObject")                                   | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__set()-detail "Defined by yii\base\BaseObject")                                       | Sets value of an object property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__unset()-detail "Defined by yii\base\BaseObject")                                   | Sets an object property to null.
| [afterLoad()](https://www.yiiframework.com/doc/api/2.0/yii-test-fixture#afterLoad()-detail "Defined by yii\test\Fixture")                                     | This method is called AFTER all fixture data have been loaded for the current test.
| [afterUnload()](https://www.yiiframework.com/doc/api/2.0/yii-test-fixture#afterUnload()-detail "Defined by yii\test\Fixture")                                 | This method is called AFTER all fixture data have been unloaded for the current test.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")                       | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")                     | Attaches a list of behaviors to the component.
| [beforeLoad()](craft-test-fixtures-elements-assetfixture.md#method-beforeload)                                                                                | This method is called BEFORE any fixture data is loaded for the current test.
| [beforeUnload()](craft-test-fixtures-elements-assetfixture.md#method-beforeunload)                                                                            | This method is called BEFORE any fixture data is unloaded for the current test.
| [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail "Defined by yii\base\Component")                                 | Returns a list of behaviors that this component should behave as.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canGetProperty()-detail "Defined by yii\base\BaseObject")                     | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canSetProperty()-detail "Defined by yii\base\BaseObject")                     | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                               | Returns the fully qualified name of this class.
| [count()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait#count()-detail "Defined by yii\base\ArrayAccessTrait")                           | Returns the number of data items.
| [detachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehavior()-detail "Defined by yii\base\Component")                       | Detaches a behavior from the component.
| [detachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehaviors()-detail "Defined by yii\base\Component")                     | Detaches all behaviors from the component.
| [ensureBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#ensureBehaviors()-detail "Defined by yii\base\Component")                     | Makes sure that the behaviors declared in [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail) are attached to this component.
| [generateElementQuery()](craft-test-fixtures-elements-elementfixture.md#method-generateelementquery "Defined by craft\test\fixtures\elements\ElementFixture") |
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")                             | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")                           | Returns all behaviors attached to this component.
| [getElement()](craft-test-fixtures-elements-assetfixture.md#method-getelement)                                                                                | Get asset model.
| [getIterator()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait#getIterator()-detail "Defined by yii\base\ArrayAccessTrait")               | Returns an iterator for traversing the data.
| [getModel()](craft-test-fixtures-elements-elementfixture.md#method-getmodel "Defined by craft\test\fixtures\elements\ElementFixture")                         | Returns the AR model by the specified model name.
| [getTableSchema()](https://www.yiiframework.com/doc/api/2.0/yii-test-activefixture#getTableSchema()-detail "Defined by yii\test\ActiveFixture")               |
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component")                   | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")                               | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")                           | Returns a value indicating whether a property is defined.
| [init()](craft-test-fixtures-elements-assetfixture.md#method-init)                                                                                            | Initializes the object.
| [load()](craft-test-fixtures-elements-elementfixture.md#method-load "Defined by craft\test\fixtures\elements\ElementFixture")                                 | Loads the fixture.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                                             | Detaches an existing event handler from this component.
| [offsetExists()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait#offsetExists()-detail "Defined by yii\base\ArrayAccessTrait")             | This method is required by the interface [ArrayAccess](http://php.net/class.arrayaccess).
| [offsetGet()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait#offsetGet()-detail "Defined by yii\base\ArrayAccessTrait")                   | This method is required by the interface [ArrayAccess](http://php.net/class.arrayaccess).
| [offsetSet()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait#offsetSet()-detail "Defined by yii\base\ArrayAccessTrait")                   | This method is required by the interface [ArrayAccess](http://php.net/class.arrayaccess).
| [offsetUnset()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayaccesstrait#offsetUnset()-detail "Defined by yii\base\ArrayAccessTrait")               | This method is required by the interface [ArrayAccess](http://php.net/class.arrayaccess).
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                                               | Attaches an event handler to an event.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                                     | Triggers an event.
| [unload()](craft-test-fixtures-elements-elementfixture.md#method-unload "Defined by craft\test\fixtures\elements\ElementFixture")                             | Unloads the fixture.

### `beforeLoad()`





This method is called BEFORE any fixture data is loaded for the current test.








[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L112-L119)






### `beforeUnload()`





This method is called BEFORE any fixture data is unloaded for the current test.








[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L124-L129)






### `getElement()`





Get asset model.




[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L96-L107)


#### Arguments

- `$data` ([array](http://php.net/language.types.array))

#### Returns

[craft\base\Element](craft-base-element.md)



### `init()`





Initializes the object.



This method is invoked at the end of the constructor after the object is initialized with the
given configuration.




[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L63-L88)








## Protected Methods

| Method                                                                                                                                    | Description
| ----------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------
| [getData()](https://www.yiiframework.com/doc/api/2.0/yii-test-activefixture#getData()-detail "Defined by yii\test\ActiveFixture")         | Returns the fixture data.
| [isPrimaryKey()](craft-test-fixtures-elements-assetfixture.md#method-isprimarykey)                                                        | See if an element's handle is a primary key.
| [loadData()](https://www.yiiframework.com/doc/api/2.0/yii-test-filefixturetrait#loadData()-detail "Defined by yii\test\FileFixtureTrait") | Returns the fixture data.
| [resetTable()](https://www.yiiframework.com/doc/api/2.0/yii-test-activefixture#resetTable()-detail "Defined by yii\test\ActiveFixture")   | Removes all existing data from the specified table and resets sequence number to 1 (if any).

### `isPrimaryKey()`





See if an element's handle is a primary key.








[View source](https://github.com/craftcms/cms/blob/master/src/test/fixtures/elements/AssetFixture.php#L134-L137)


#### Arguments

- `$key` ([string](http://php.net/language.types.string))

#### Returns

[boolean](http://php.net/language.types.boolean)







