---
title: craft\commerce\migrations\Install
code:
  - php
  - twig
---

# Install

Type

:   Class

Namespace

:   craft\commerce\migrations

Inherits

:   [craft\commerce\migrations\Install](craft-commerce-migrations-install.md) &raquo;
[craft\db\Migration](https://docs.craftcms.com/api/v3/craft-db-migration.html) &raquo;
[yii\db\Migration](https://www.yiiframework.com/doc/api/2.0/yii-db-migration) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable), [yii\db\MigrationInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-migrationinterface)

Uses traits

:   [yii\db\SchemaBuilderTrait](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait)

Since

:   2.0



Installation Migration





[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php)


## Public Properties

| Property                                                                                                                                 | Description
| ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component")               | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [compact](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#$compact-detail "Defined by yii\db\Migration")                       | [boolean](http://php.net/language.types.boolean) – Indicates whether the console output should be compacted.
| [db](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#$db-detail "Defined by yii\db\Migration")                                 | [yii\db\Connection](https://www.yiiframework.com/doc/api/2.0/yii-db-connection), [array](http://php.net/language.types.array), [string](http://php.net/language.types.string) – The DB connection object or the application component ID of the DB connection that this migration should work with.
| [maxSqlOutputLength](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#$maxSqlOutputLength-detail "Defined by yii\db\Migration") | [integer](http://php.net/language.types.integer) – Max number of characters of the SQL outputted.





## Public Methods

| Method                                                                                                                                              | Description
| --------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__call()-detail "Defined by yii\base\Component")                             | Calls the named method which is not a class method.
| [__clone()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__clone()-detail "Defined by yii\base\Component")                           | This method is called after the object is created by cloning an existing one.
| [__construct()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#__construct()-detail "Defined by yii\base\BaseObject")                 | Constructor.
| [__get()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__get()-detail "Defined by yii\base\Component")                               | Returns the value of a component property.
| [__isset()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__isset()-detail "Defined by yii\base\Component")                           | Checks if a property is set, i.e. defined and not null.
| [__set()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__set()-detail "Defined by yii\base\Component")                               | Sets the value of a component property.
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__unset()-detail "Defined by yii\base\Component")                           | Sets a component property to be null.
| [_defaultDonationPurchasable()](craft-commerce-migrations-install.md#method-defaultdonationpurchasable)                                             | Add the donation purchasable
| [addColumn()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#addColumn()-detail "Defined by yii\db\Migration")                           | Builds and executes a SQL statement for adding a new DB column.
| [addCommentOnColumn()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#addCommentOnColumn()-detail "Defined by yii\db\Migration")         | Builds and execute a SQL statement for adding comment to column.
| [addCommentOnTable()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#addCommentOnTable()-detail "Defined by yii\db\Migration")           | Builds a SQL statement for adding comment to table.
| [addForeignKey()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-addforeignkey "Defined by craft\db\Migration")                    | Builds a SQL statement for adding a foreign key constraint to an existing table.
| [addForeignKeys()](craft-commerce-migrations-install.md#method-addforeignkeys)                                                                      | Adds the foreign keys.
| [addPrimaryKey()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-addprimarykey "Defined by craft\db\Migration")                    | Builds and executes a SQL statement for creating a primary key.
| [alterColumn()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#alterColumn()-detail "Defined by yii\db\Migration")                       | Builds and executes a SQL statement for changing the definition of a column.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")             | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")           | Attaches a list of behaviors to the component.
| [batchInsert()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-batchinsert "Defined by craft\db\Migration")                        | Creates and executes an batch INSERT SQL statement.
| [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail "Defined by yii\base\Component")                       | Returns a list of behaviors that this component should behave as.
| [bigInteger()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#bigInteger()-detail "Defined by yii\db\SchemaBuilderTrait")       | Creates a bigint column.
| [bigPrimaryKey()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#bigPrimaryKey()-detail "Defined by yii\db\SchemaBuilderTrait") | Creates a big primary key column.
| [binary()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#binary()-detail "Defined by yii\db\SchemaBuilderTrait")               | Creates a binary column.
| [boolean()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#boolean()-detail "Defined by yii\db\SchemaBuilderTrait")             | Creates a boolean column.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canGetProperty()-detail "Defined by yii\base\Component")             | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canSetProperty()-detail "Defined by yii\base\Component")             | Returns a value indicating whether a property can be set.
| [char()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#char()-detail "Defined by yii\db\SchemaBuilderTrait")                   | Creates a char column.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                     | Returns the fully qualified name of this class.
| [createIndex()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-createindex "Defined by craft\db\Migration")                        | Builds and executes a SQL statement for creating a new index.
| [createIndexes()](craft-commerce-migrations-install.md#method-createindexes)                                                                        | Creates the indexes.
| [createTable()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#createTable()-detail "Defined by yii\db\Migration")                       | Builds and executes a SQL statement for creating a new DB table.
| [createTables()](craft-commerce-migrations-install.md#method-createtables)                                                                          | Creates the tables for Craft Commerce
| [date()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#date()-detail "Defined by yii\db\SchemaBuilderTrait")                   | Creates a date column.
| [dateTime()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#dateTime()-detail "Defined by yii\db\SchemaBuilderTrait")           | Creates a datetime column.
| [decimal()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#decimal()-detail "Defined by yii\db\SchemaBuilderTrait")             | Creates a decimal column.
| [delete()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#delete()-detail "Defined by yii\db\Migration")                                 | Creates and executes a DELETE SQL statement.
| [detachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehavior()-detail "Defined by yii\base\Component")             | Detaches a behavior from the component.
| [detachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehaviors()-detail "Defined by yii\base\Component")           | Detaches all behaviors from the component.
| [double()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#double()-detail "Defined by yii\db\SchemaBuilderTrait")               | Creates a double column.
| [down()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-down "Defined by craft\db\Migration")                                      | This method contains the logic to be executed when removing this migration.
| [dropColumn()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#dropColumn()-detail "Defined by yii\db\Migration")                         | Builds and executes a SQL statement for dropping a DB column.
| [dropCommentFromColumn()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#dropCommentFromColumn()-detail "Defined by yii\db\Migration")   | Builds and execute a SQL statement for dropping comment from column.
| [dropCommentFromTable()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#dropCommentFromTable()-detail "Defined by yii\db\Migration")     | Builds a SQL statement for dropping comment from table.
| [dropForeignKey()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#dropForeignKey()-detail "Defined by yii\db\Migration")                 | Builds a SQL statement for dropping a foreign key constraint.
| [dropForeignKeys()](craft-commerce-migrations-install.md#method-dropforeignkeys)                                                                    | Removes the foreign keys.
| [dropIndex()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#dropIndex()-detail "Defined by yii\db\Migration")                           | Builds and executes a SQL statement for dropping an index.
| [dropPrimaryKey()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#dropPrimaryKey()-detail "Defined by yii\db\Migration")                 | Builds and executes a SQL statement for dropping a primary key.
| [dropProjectConfig()](craft-commerce-migrations-install.md#method-dropprojectconfig)                                                                | Deletes the project config entry.
| [dropTable()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#dropTable()-detail "Defined by yii\db\Migration")                           | Builds and executes a SQL statement for dropping a DB table.
| [dropTableIfExists()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-droptableifexists "Defined by craft\db\Migration")            | Creates and executes a SQL statement for dropping a DB table, if it exists.
| [dropTables()](craft-commerce-migrations-install.md#method-droptables)                                                                              | Drop the tables
| [ensureBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#ensureBehaviors()-detail "Defined by yii\base\Component")           | Makes sure that the behaviors declared in [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail) are attached to this component.
| [enum()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-enum "Defined by craft\db\Migration")                                      | Creates an enum column for MySQL and PostgreSQL, or a string column with a check constraint for others.
| [execute()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#execute()-detail "Defined by yii\db\Migration")                               | Executes a SQL statement.
| [float()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#float()-detail "Defined by yii\db\SchemaBuilderTrait")                 | Creates a float column.
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")                   | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")                 | Returns all behaviors attached to this component.
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component")         | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasMethod()-detail "Defined by yii\base\Component")                       | Returns a value indicating whether a method is defined.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasProperty()-detail "Defined by yii\base\Component")                   | Returns a value indicating whether a property is defined for this component.
| [init()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#init()-detail "Defined by yii\db\Migration")                                     | Initializes the migration.
| [insert()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-insert "Defined by craft\db\Migration")                                  | Creates and executes an INSERT SQL statement.
| [insertDefaultData()](craft-commerce-migrations-install.md#method-insertdefaultdata)                                                                | Insert the default data.
| [integer()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#integer()-detail "Defined by yii\db\SchemaBuilderTrait")             | Creates an integer column.
| [json()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#json()-detail "Defined by yii\db\SchemaBuilderTrait")                   | Creates a JSON column.
| [longText()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-longtext "Defined by craft\db\Migration")                              | Creates a longtext column for MySQL, or text column for others.
| [mediumText()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-mediumtext "Defined by craft\db\Migration")                          | Creates a mediumtext column for MySQL, or text column for others.
| [money()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#money()-detail "Defined by yii\db\SchemaBuilderTrait")                 | Creates a money column.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                                   | Detaches an existing event handler from this component.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                                     | Attaches an event handler to an event.
| [primaryKey()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#primaryKey()-detail "Defined by yii\db\SchemaBuilderTrait")       | Creates a primary key column.
| [renameColumn()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#renameColumn()-detail "Defined by yii\db\Migration")                     | Builds and executes a SQL statement for renaming a column.
| [renameSequence()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-renamesequence "Defined by craft\db\Migration")                  | Creates and executes a SQL statement for renaming a DB sequence.
| [renameTable()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#renameTable()-detail "Defined by yii\db\Migration")                       | Builds and executes a SQL statement for renaming a DB table.
| [replace()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-replace "Defined by craft\db\Migration")                                | Creates and executes a SQL statement for replacing some text with other text in a given table column.
| [restore()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-restore "Defined by craft\db\Migration")                                | Creates and executes a SQL statement for restoring a soft-deleted row.
| [safeDown()](craft-commerce-migrations-install.md#method-safedown)                                                                                  | This method contains the logic to be executed when removing this migration.
| [safeUp()](craft-commerce-migrations-install.md#method-safeup)                                                                                      | This method contains the logic to be executed when applying this migration.
| [smallInteger()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#smallInteger()-detail "Defined by yii\db\SchemaBuilderTrait")   | Creates a smallint column.
| [softDelete()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-softdelete "Defined by craft\db\Migration")                          | Creates and executes a SQL statement for soft-deleting a row.
| [string()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#string()-detail "Defined by yii\db\SchemaBuilderTrait")               | Creates a string column.
| [text()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#text()-detail "Defined by yii\db\SchemaBuilderTrait")                   | Creates a text column.
| [time()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#time()-detail "Defined by yii\db\SchemaBuilderTrait")                   | Creates a time column.
| [timestamp()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#timestamp()-detail "Defined by yii\db\SchemaBuilderTrait")         | Creates a timestamp column.
| [tinyInteger()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#tinyInteger()-detail "Defined by yii\db\SchemaBuilderTrait")     | Creates a tinyint column. If tinyint is not supported by the DBMS, smallint will be used.
| [tinyText()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-tinytext "Defined by craft\db\Migration")                              | Creates a tinytext column for MySQL, or text column for others.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                           | Triggers an event.
| [truncateTable()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#truncateTable()-detail "Defined by yii\db\Migration")                   | Builds and executes a SQL statement for truncating a DB table.
| [uid()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-uid "Defined by craft\db\Migration")                                        | Shortcut for creating a uid column
| [up()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-up "Defined by craft\db\Migration")                                          | This method contains the logic to be executed when applying this migration.
| [update()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-update "Defined by craft\db\Migration")                                  | Creates and executes an UPDATE SQL statement.
| [upsert()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-upsert "Defined by craft\db\Migration")                                  | Creates and executes a command to insert rows into a database table if they do not already exist (matching unique constraints), or update them if they do.

### `_defaultDonationPurchasable()`





Add the donation purchasable




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L1609-L1615)






### `addForeignKeys()`





Adds the foreign keys.




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L1008-L1095)






### `createIndexes()`





Creates the indexes.




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L894-L1003)






### `createTables()`





Creates the tables for Craft Commerce




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L92-L823)






### `dropForeignKeys()`





Removes the foreign keys.




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L1100-L1144)






### `dropProjectConfig()`





Deletes the project config entry.




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L886-L889)






### `dropTables()`





Drop the tables




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L828-L881)






### `insertDefaultData()`





Insert the default data.




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L1149-L1170)






### `safeDown()`





This method contains the logic to be executed when removing this migration.



This method differs from [down()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-down) in that the DB logic implemented here will
be enclosed within a DB transaction.
Child classes may implement this method instead of [down()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-down) if the DB logic
needs to be within a transaction.

Note: Not all DBMS support transactions. And some DB queries cannot be put into a transaction. For some examples,
please refer to [implicit commit](http://dev.mysql.com/doc/refman/5.7/en/implicit-commit.html).




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L77-L86)



#### Returns

[boolean](http://php.net/language.types.boolean) – Return a false value to indicate the migration fails
and should not proceed further. All other return values mean the migration succeeds.



### `safeUp()`





This method contains the logic to be executed when applying this migration.



This method differs from [up()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-up) in that the DB logic implemented here will
be enclosed within a DB transaction.
Child classes may implement this method instead of [up()](https://docs.craftcms.com/api/v3/craft-db-migration.html#method-up) if the DB logic
needs to be within a transaction.

Note: Not all DBMS support transactions. And some DB queries cannot be put into a transaction. For some examples,
please refer to [implicit commit](http://dev.mysql.com/doc/refman/5.7/en/implicit-commit.html).




[View source](https://github.com/craftcms/commerce/blob/master/src/migrations/Install.php#L64-L72)



#### Returns

[boolean](http://php.net/language.types.boolean) – Return a false value to indicate the migration fails
and should not proceed further. All other return values mean the migration succeeds.





## Protected Methods

| Method                                                                                                                              | Description
| ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------
| [beginCommand()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#beginCommand()-detail "Defined by yii\db\Migration")     | Prepares for a command to be executed, and outputs to the console.
| [endCommand()](https://www.yiiframework.com/doc/api/2.0/yii-db-migration#endCommand()-detail "Defined by yii\db\Migration")         | Finalizes after the command has been executed, and outputs to the console the time elapsed.
| [getDb()](https://www.yiiframework.com/doc/api/2.0/yii-db-schemabuildertrait#getDb()-detail "Defined by yii\db\SchemaBuilderTrait") |





