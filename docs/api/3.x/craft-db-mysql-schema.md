---
title: craft\db\mysql\Schema
code:
  - php
  - twig
---

# Schema

Type

:   Class

Namespace

:   craft\db\mysql

Inherits

:   [craft\db\mysql\Schema](craft-db-mysql-schema.md) &raquo;
[yii\db\mysql\Schema](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema) &raquo;
[yii\db\Schema](https://www.yiiframework.com/doc/api/2.0/yii-db-schema) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable), [yii\db\ConstraintFinderInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfinderinterface)

Uses traits

:   [yii\db\ConstraintFinderTrait](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait)

Since

:   3.0.0









[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php)


## Public Properties

| Property                                                                                                                                                           | Description
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [columnSchemaClass](craft-db-mysql-schema.md#columnschemaclass)                                                                                                    | [string](http://php.net/language.types.string), [array](http://php.net/language.types.array) – Column schema class or class config
| [db](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$db-detail "Defined by yii\db\Schema")                                                                 | [yii\db\Connection](https://www.yiiframework.com/doc/api/2.0/yii-db-connection) – The database connection
| [defaultBackupCommand](craft-db-mysql-schema.md#defaultbackupcommand)                                                                                              | [string](http://php.net/language.types.string) – The command to execute
| [defaultRestoreCommand](craft-db-mysql-schema.md#defaultrestorecommand)                                                                                            | [string](http://php.net/language.types.string) – The command to execute
| [defaultSchema](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$defaultSchema-detail "Defined by yii\db\Schema")                                           | [string](http://php.net/language.types.string) – The default schema name used for the current session.
| [exceptionMap](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$exceptionMap-detail "Defined by yii\db\Schema")                                             | [array](http://php.net/language.types.array) – Map of DB errors and corresponding exceptions If left part is found in DB error message exception class from the right part is used.
| [lastInsertID](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$lastInsertID-detail "Defined by yii\db\Schema")                                             | [string](http://php.net/language.types.string) – The row ID of the last row inserted, or the last value retrieved from the sequence object
| [maxObjectNameLength](craft-db-mysql-schema.md#maxobjectnamelength)                                                                                                | [integer](http://php.net/language.types.integer) – The maximum length that objects' names can be.
| [queryBuilder](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$queryBuilder-detail "Defined by yii\db\Schema")                                             | [yii\db\QueryBuilder](https://www.yiiframework.com/doc/api/2.0/yii-db-querybuilder) – The query builder for this connection.
| [schemaChecks](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#$schemaChecks-detail "Defined by yii\db\ConstraintFinderTrait")               | `\yii\db\CheckConstraint[][]` – Check constraints for all tables in the database.
| [schemaDefaultValues](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#$schemaDefaultValues-detail "Defined by yii\db\ConstraintFinderTrait") | [yii\db\DefaultValueConstraint](https://www.yiiframework.com/doc/api/2.0/yii-db-defaultvalueconstraint) – Default value constraints for all tables in the database.
| [schemaForeignKeys](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#$schemaForeignKeys-detail "Defined by yii\db\ConstraintFinderTrait")     | `\yii\db\ForeignKeyConstraint[][]` – Foreign keys for all tables in the database.
| [schemaIndexes](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#$schemaIndexes-detail "Defined by yii\db\ConstraintFinderTrait")             | `\yii\db\IndexConstraint[][]` – Indexes for all tables in the database.
| [schemaNames](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$schemaNames-detail "Defined by yii\db\Schema")                                               | [string](http://php.net/language.types.string)[] – All schema names in the database, except system schemas.
| [schemaPrimaryKeys](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#$schemaPrimaryKeys-detail "Defined by yii\db\ConstraintFinderTrait")     | [yii\db\Constraint](https://www.yiiframework.com/doc/api/2.0/yii-db-constraint) – Primary keys for all tables in the database.
| [schemaUniques](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#$schemaUniques-detail "Defined by yii\db\ConstraintFinderTrait")             | `\yii\db\Constraint[][]` – Unique constraints for all tables in the database.
| [serverVersion](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$serverVersion-detail "Defined by yii\db\Schema")                                           | [string](http://php.net/language.types.string) – Server version as a string.
| [tableNames](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$tableNames-detail "Defined by yii\db\Schema")                                                 | [string](http://php.net/language.types.string)[] – All table names in the database.
| [tableSchemas](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$tableSchemas-detail "Defined by yii\db\Schema")                                             | [yii\db\TableSchema](https://www.yiiframework.com/doc/api/2.0/yii-db-tableschema) – The metadata for all tables in the database.
| [transactionIsolationLevel](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#$transactionIsolationLevel-detail "Defined by yii\db\Schema")                   | [string](http://php.net/language.types.string) – The transaction isolation level to use for this transaction.
| [typeMap](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#$typeMap-detail "Defined by yii\db\mysql\Schema")                                           | [array](http://php.net/language.types.array) – Mapping from physical column types (keys) to abstract column types (values)

### `columnSchemaClass`



Type

:   [string](http://php.net/language.types.string), [array](http://php.net/language.types.array)





Column schema class or class config





[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L38)



### `defaultBackupCommand`



Type

:   [string](http://php.net/language.types.string)

Access

:   Read-only



The command to execute



[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php)



### `defaultRestoreCommand`



Type

:   [string](http://php.net/language.types.string)

Access

:   Read-only



The command to execute



[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php)



### `maxObjectNameLength`



Type

:   [integer](http://php.net/language.types.integer)



The maximum length that objects' names can be.



[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L43)





## Protected Properties

| Property                                                                                                                                           | Description
| -------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------
| [columnQuoteCharacter](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#$columnQuoteCharacter-detail "Defined by yii\db\mysql\Schema") | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[] – Character used to quote column names.
| [tableQuoteCharacter](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#$tableQuoteCharacter-detail "Defined by yii\db\mysql\Schema")   | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[] – Character used to quote schema, table, etc.



## Public Methods

| Method                                                                                                                                                                      | Description
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__call()-detail "Defined by yii\base\BaseObject")                                                   | Calls the named method which is not a class method.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")                                         | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__get()-detail "Defined by yii\base\BaseObject")                                                     | Returns the value of an object property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__isset()-detail "Defined by yii\base\BaseObject")                                                 | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__set()-detail "Defined by yii\base\BaseObject")                                                     | Sets value of an object property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__unset()-detail "Defined by yii\base\BaseObject")                                                 | Sets an object property to null.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canGetProperty()-detail "Defined by yii\base\BaseObject")                                   | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#canSetProperty()-detail "Defined by yii\base\BaseObject")                                   | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                                             | Returns the fully qualified name of this class.
| [convertException()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#convertException()-detail "Defined by yii\db\Schema")                                           | Converts a DB exception to a more concrete one if possible.
| [createColumnSchemaBuilder()](craft-db-mysql-schema.md#method-createcolumnschemabuilder)                                                                                    | Create a column schema builder instance giving the type and value precision.
| [createQueryBuilder()](craft-db-mysql-schema.md#method-createquerybuilder)                                                                                                  | Creates a query builder for the database.
| [createSavepoint()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#createSavepoint()-detail "Defined by yii\db\Schema")                                             | Creates a new savepoint.
| [findIndexes()](craft-db-mysql-schema.md#method-findindexes)                                                                                                                | Returns all indexes for the given table. Each array element is of the following structure:
| [findUniqueIndexes()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#findUniqueIndexes()-detail "Defined by yii\db\mysql\Schema")                             | Returns all unique indexes for the given table.
| [getDefaultBackupCommand()](craft-db-mysql-schema.md#method-getdefaultbackupcommand)                                                                                        | Returns the default backup command to execute.
| [getDefaultRestoreCommand()](craft-db-mysql-schema.md#method-getdefaultrestorecommand)                                                                                      | Returns the default database restore command to execute.
| [getLastInsertID()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getLastInsertID()-detail "Defined by yii\db\Schema")                                             | Returns the ID of the last inserted row or sequence value.
| [getPdoType()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getPdoType()-detail "Defined by yii\db\Schema")                                                       | Determines the PDO type for the given PHP data value.
| [getQueryBuilder()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getQueryBuilder()-detail "Defined by yii\db\Schema")                                             |
| [getRawTableName()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getRawTableName()-detail "Defined by yii\db\Schema")                                             | Returns the actual name of a given table name.
| [getSchemaChecks()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getSchemaChecks()-detail "Defined by yii\db\ConstraintFinderTrait")               | Returns check constraints for all tables in the database.
| [getSchemaDefaultValues()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getSchemaDefaultValues()-detail "Defined by yii\db\ConstraintFinderTrait") | Returns default value constraints for all tables in the database.
| [getSchemaForeignKeys()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getSchemaForeignKeys()-detail "Defined by yii\db\ConstraintFinderTrait")     | Returns foreign keys for all tables in the database.
| [getSchemaIndexes()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getSchemaIndexes()-detail "Defined by yii\db\ConstraintFinderTrait")             | Returns indexes for all tables in the database.
| [getSchemaNames()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getSchemaNames()-detail "Defined by yii\db\Schema")                                               | Returns all schema names in the database, except system schemas.
| [getSchemaPrimaryKeys()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getSchemaPrimaryKeys()-detail "Defined by yii\db\ConstraintFinderTrait")     | Returns primary keys for all tables in the database.
| [getSchemaUniques()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getSchemaUniques()-detail "Defined by yii\db\ConstraintFinderTrait")             | Returns unique constraints for all tables in the database.
| [getServerVersion()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getServerVersion()-detail "Defined by yii\db\Schema")                                           | Returns a server version as a string comparable by `\version_compare()`.
| [getTableChecks()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getTableChecks()-detail "Defined by yii\db\ConstraintFinderTrait")                 | Obtains the check constraints information for the named table.
| [getTableDefaultValues()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getTableDefaultValues()-detail "Defined by yii\db\ConstraintFinderTrait")   | Obtains the default value constraints information for the named table.
| [getTableForeignKeys()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getTableForeignKeys()-detail "Defined by yii\db\ConstraintFinderTrait")       | Obtains the foreign keys information for the named table.
| [getTableIndexes()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getTableIndexes()-detail "Defined by yii\db\ConstraintFinderTrait")               | Obtains the indexes information for the named table.
| [getTableNames()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getTableNames()-detail "Defined by yii\db\Schema")                                                 | Returns all table names in the database.
| [getTablePrimaryKey()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getTablePrimaryKey()-detail "Defined by yii\db\ConstraintFinderTrait")         | Obtains the primary key for the named table.
| [getTableSchema()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getTableSchema()-detail "Defined by yii\db\Schema")                                               | Obtains the metadata for the named table.
| [getTableSchemas()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getTableSchemas()-detail "Defined by yii\db\Schema")                                             | Returns the metadata for all tables in the database.
| [getTableUniques()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getTableUniques()-detail "Defined by yii\db\ConstraintFinderTrait")               | Obtains the unique constraints information for the named table.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasMethod()-detail "Defined by yii\base\BaseObject")                                             | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#hasProperty()-detail "Defined by yii\base\BaseObject")                                         | Returns a value indicating whether a property is defined.
| [init()](craft-db-mysql-schema.md#method-init)                                                                                                                              | Initializes the object.
| [insert()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#insert()-detail "Defined by yii\db\Schema")                                                               | Executes the INSERT command, returning primary key values.
| [isReadQuery()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#isReadQuery()-detail "Defined by yii\db\Schema")                                                     | Returns a value indicating whether a SQL statement is for read purpose.
| [quoteColumnName()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#quoteColumnName()-detail "Defined by yii\db\Schema")                                             | Quotes a column name for use in a query.
| [quoteDatabaseName()](craft-db-mysql-schema.md#method-quotedatabasename)                                                                                                    | Quotes a database name for use in a query.
| [quoteSimpleColumnName()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#quoteSimpleColumnName()-detail "Defined by yii\db\Schema")                                 | Quotes a simple column name for use in a query.
| [quoteSimpleTableName()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#quoteSimpleTableName()-detail "Defined by yii\db\Schema")                                   | Quotes a simple table name for use in a query.
| [quoteTableName()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#quoteTableName()-detail "Defined by yii\db\Schema")                                               | Quotes a table name for use in a query.
| [quoteValue()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#quoteValue()-detail "Defined by yii\db\Schema")                                                       | Quotes a string value for use in a query.
| [refresh()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#refresh()-detail "Defined by yii\db\Schema")                                                             | Refreshes the schema.
| [refreshTableSchema()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#refreshTableSchema()-detail "Defined by yii\db\Schema")                                       | Refreshes the particular table schema.
| [releaseSavepoint()](craft-db-mysql-schema.md#method-releasesavepoint)                                                                                                      | Releases an existing savepoint.
| [rollBackSavepoint()](craft-db-mysql-schema.md#method-rollbacksavepoint)                                                                                                    | Rolls back to a previously created savepoint.
| [setTransactionIsolationLevel()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#setTransactionIsolationLevel()-detail "Defined by yii\db\Schema")                   | Sets the isolation level of the current transaction.
| [supportsSavepoint()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#supportsSavepoint()-detail "Defined by yii\db\Schema")                                         |
| [unquoteSimpleColumnName()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#unquoteSimpleColumnName()-detail "Defined by yii\db\Schema")                             | Unquotes a simple column name.
| [unquoteSimpleTableName()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#unquoteSimpleTableName()-detail "Defined by yii\db\Schema")                               | Unquotes a simple table name.

### `createColumnSchemaBuilder()`





Create a column schema builder instance giving the type and value precision.

This method may be overridden by child classes to create a DBMS-specific column schema builder.


[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L132-L135)


#### Arguments

- `$type` ([string](http://php.net/language.types.string)) – Type of the column. See [craft\db\mysql\ColumnSchemaBuilder::$type](https://www.yiiframework.com/doc/api/2.0/yii-db-columnschemabuilder#$type-detail).
- `$length` ([integer](http://php.net/language.types.integer), [string](http://php.net/language.types.string), [array](http://php.net/language.types.array)) – Length or precision of the column. See [craft\db\mysql\ColumnSchemaBuilder::$length](https://www.yiiframework.com/doc/api/2.0/yii-db-columnschemabuilder#$length-detail).

#### Returns

[craft\db\mysql\ColumnSchemaBuilder](craft-db-mysql-columnschemabuilder.md) – Column schema builder instance



### `createQueryBuilder()`





Creates a query builder for the database.

This method may be overridden by child classes to create a DBMS-specific query builder.


[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L65-L70)



#### Returns

[craft\db\mysql\QueryBuilder](craft-db-mysql-querybuilder.md) – Query builder instance



### `findIndexes()`





Returns all indexes for the given table. Each array element is of the following structure:

```php
[
    'IndexName' => [
        'columns' => ['col1' [, ...]],
        'unique' => false
    ],
]
```


[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L238-L258)


#### Arguments

- `$tableName` ([string](http://php.net/language.types.string)) – The name of the table to get the indexes for.

#### Returns

[array](http://php.net/language.types.array) – All indexes for the given table.

#### Throws

- [yii\base\NotSupportedException](https://www.yiiframework.com/doc/api/2.0/yii-base-notsupportedexception)


### `getDefaultBackupCommand()`





Returns the default backup command to execute.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L144-L206)


#### Arguments

- `$ignoreTables`

#### Returns

[string](http://php.net/language.types.string) – The command to execute

#### Throws

- [yii\base\ErrorException](https://www.yiiframework.com/doc/api/2.0/yii-base-errorexception)


### `getDefaultRestoreCommand()`





Returns the default database restore command to execute.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L214-L220)



#### Returns

[string](http://php.net/language.types.string) – The command to execute

#### Throws

- [yii\base\ErrorException](https://www.yiiframework.com/doc/api/2.0/yii-base-errorexception)


### `init()`





Initializes the object.



This method is invoked at the end of the constructor after the object is initialized with the
given configuration.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L48-L56)






### `quoteDatabaseName()`





Quotes a database name for use in a query.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L78-L81)


#### Arguments

- `$name` ([string](http://php.net/language.types.string))

#### Returns

[string](http://php.net/language.types.string)



### `releaseSavepoint()`





Releases an existing savepoint.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L89-L101)


#### Arguments

- `$name` ([string](http://php.net/language.types.string)) – The savepoint name.


#### Throws

- [yii\db\Exception](https://www.yiiframework.com/doc/api/2.0/yii-db-exception)


### `rollBackSavepoint()`





Rolls back to a previously created savepoint.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L109-L121)


#### Arguments

- `$name` ([string](http://php.net/language.types.string)) – The savepoint name.


#### Throws

- [yii\db\Exception](https://www.yiiframework.com/doc/api/2.0/yii-db-exception)




## Protected Methods

| Method                                                                                                                                                                      | Description
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------
| [createColumnSchema()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#createColumnSchema()-detail "Defined by yii\db\Schema")                                       | Creates a column schema for the database.
| [findColumns()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#findColumns()-detail "Defined by yii\db\mysql\Schema")                                         | Collects the metadata of table columns.
| [findConstraints()](craft-db-mysql-schema.md#method-findconstraints)                                                                                                        | Collects extra foreign key information details for the given table.
| [findSchemaNames()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#findSchemaNames()-detail "Defined by yii\db\Schema")                                             | Returns all schema names in the database, including the default one but not system schemas.
| [findTableNames()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#findTableNames()-detail "Defined by yii\db\mysql\Schema")                                   | Returns all table names in the database.
| [getCacheKey()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getCacheKey()-detail "Defined by yii\db\Schema")                                                     | Returns the cache key for the specified table name.
| [getCacheTag()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getCacheTag()-detail "Defined by yii\db\Schema")                                                     | Returns the cache tag name.
| [getColumnPhpType()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getColumnPhpType()-detail "Defined by yii\db\Schema")                                           | Extracts the PHP type from abstract DB type.
| [getCreateTableSql()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#getCreateTableSql()-detail "Defined by yii\db\mysql\Schema")                             | Gets the CREATE TABLE sql string.
| [getSchemaMetadata()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getSchemaMetadata()-detail "Defined by yii\db\ConstraintFinderTrait")           | Returns the metadata of the given type for all tables in the given schema.
| [getTableMetadata()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#getTableMetadata()-detail "Defined by yii\db\ConstraintFinderTrait")             | Returns the metadata of the given type for the given table.
| [getTableNameParts()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#getTableNameParts()-detail "Defined by yii\db\Schema")                                         | Splits full table name into parts
| [isOldMysql()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#isOldMysql()-detail "Defined by yii\db\mysql\Schema")                                           |
| [loadColumnSchema()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#loadColumnSchema()-detail "Defined by yii\db\mysql\Schema")                               | Loads the column information into a [yii\db\mysql\ColumnSchema](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-columnschema) object.
| [loadTableChecks()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#loadTableChecks()-detail "Defined by yii\db\ConstraintFinderTrait")               | Loads all check constraints for the given table.
| [loadTableDefaultValues()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#loadTableDefaultValues()-detail "Defined by yii\db\ConstraintFinderTrait") | Loads all default value constraints for the given table.
| [loadTableForeignKeys()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#loadTableForeignKeys()-detail "Defined by yii\db\ConstraintFinderTrait")     | Loads all foreign keys for the given table.
| [loadTableIndexes()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#loadTableIndexes()-detail "Defined by yii\db\ConstraintFinderTrait")             | Loads all indexes for the given table.
| [loadTablePrimaryKey()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#loadTablePrimaryKey()-detail "Defined by yii\db\ConstraintFinderTrait")       | Loads a primary key for the given table.
| [loadTableSchema()](craft-db-mysql-schema.md#method-loadtableschema)                                                                                                        | Loads the metadata for the specified table.
| [loadTableUniques()](https://www.yiiframework.com/doc/api/2.0/yii-db-constraintfindertrait#loadTableUniques()-detail "Defined by yii\db\ConstraintFinderTrait")             | Loads all unique constraints for the given table.
| [normalizePdoRowKeyCase()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#normalizePdoRowKeyCase()-detail "Defined by yii\db\Schema")                               | Changes row's array key case to lower if PDO's one is set to uppercase.
| [resolveTableName()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#resolveTableName()-detail "Defined by yii\db\mysql\Schema")                               | Resolves the table name and schema name (if any).
| [resolveTableNames()](https://www.yiiframework.com/doc/api/2.0/yii-db-mysql-schema#resolveTableNames()-detail "Defined by yii\db\mysql\Schema")                             | Resolves the table name and schema name (if any).
| [setTableMetadata()](https://www.yiiframework.com/doc/api/2.0/yii-db-schema#setTableMetadata()-detail "Defined by yii\db\Schema")                                           | Sets the metadata of the given type for the given table.

### `findConstraints()`





Collects extra foreign key information details for the given table.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L287-L362)


#### Arguments

- `$table` ([craft\db\TableSchema](craft-db-tableschema.md)) – The table metadata


#### Throws

- [yii\db\Exception](https://www.yiiframework.com/doc/api/2.0/yii-db-exception)


### `loadTableSchema()`





Loads the metadata for the specified table.




[View source](https://github.com/craftcms/cms/blob/master/src/db/mysql/Schema.php#L267-L279)


#### Arguments

- `$name` ([string](http://php.net/language.types.string)) – Table name

#### Returns

[craft\db\TableSchema](craft-db-tableschema.md), [null](http://php.net/language.types.null) – Driver dependent table metadata. Null if the table does not exist.

#### Throws

- [Exception](http://php.net/class.exception)




## Constants

| Constant               | Description
| ---------------------- | -------------------------------------------------------------------------------------------------------------
| `SCHEMA_CACHE_VERSION` | Schema cache version, to detect incompatibilities in cached values when the data format of the cache changes.
| `TYPE_BIGINT`          |
| `TYPE_BIGPK`           |
| `TYPE_BINARY`          |
| `TYPE_BOOLEAN`         |
| `TYPE_CHAR`            |
| `TYPE_DATE`            |
| `TYPE_DATETIME`        |
| `TYPE_DECIMAL`         |
| `TYPE_DOUBLE`          |
| `TYPE_ENUM`            |
| `TYPE_FLOAT`           |
| `TYPE_INTEGER`         |
| `TYPE_JSON`            |
| `TYPE_LONGTEXT`        |
| `TYPE_MEDIUMTEXT`      |
| `TYPE_MONEY`           |
| `TYPE_PK`              |
| `TYPE_SMALLINT`        |
| `TYPE_STRING`          |
| `TYPE_TEXT`            |
| `TYPE_TIME`            |
| `TYPE_TIMESTAMP`       |
| `TYPE_TINYINT`         |
| `TYPE_TINYTEXT`        |
| `TYPE_UBIGPK`          |
| `TYPE_UPK`             |


