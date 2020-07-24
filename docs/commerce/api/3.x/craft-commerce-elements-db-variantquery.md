---
title: craft\commerce\elements\db\VariantQuery
code:
  - php
  - twig
---

# VariantQuery

Type

:   Class

Namespace

:   craft\commerce\elements\db

Inherits

:   [craft\commerce\elements\db\VariantQuery](craft-commerce-elements-db-variantquery.md) &raquo;
[craft\elements\db\ElementQuery](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html) &raquo;
[craft\db\Query](https://docs.craftcms.com/api/v3/craft-db-query.html) &raquo;
[yii\db\Query](https://www.yiiframework.com/doc/api/2.0/yii-db-query) &raquo;
[yii\base\Component](https://www.yiiframework.com/doc/api/2.0/yii-base-component) &raquo;
[yii\base\BaseObject](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject)

Implements

:   [craft\elements\db\ElementQueryInterface](https://docs.craftcms.com/api/v3/craft-elements-db-elementqueryinterface.html), [yii\base\Configurable](https://www.yiiframework.com/doc/api/2.0/yii-base-configurable), [yii\db\ExpressionInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-expressioninterface), [yii\db\QueryInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-queryinterface)

Uses traits

:   [craft\base\ClonefixTrait](https://docs.craftcms.com/api/v3/craft-base-clonefixtrait.html), [yii\base\ArrayableTrait](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait), [yii\db\QueryTrait](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait)

Since

:   2.0



VariantQuery represents a SELECT SQL statement for variants in a way that is independent of DBMS.





[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php)


## Public Properties

| Property                                                                                                                                                  | Description
| --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [ancestorDist](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#ancestordist "Defined by craft\elements\db\ElementQuery")             | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – The maximum number of levels that results may be separated from [ancestorOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-ancestorof).
| [ancestorOf](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#ancestorof "Defined by craft\elements\db\ElementQuery")                 | [integer](http://php.net/language.types.integer), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element (or its ID) that results must be an ancestor of.
| [archived](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#archived "Defined by craft\elements\db\ElementQuery")                     | [boolean](http://php.net/language.types.boolean) – Whether to return only archived elements.
| [asArray](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#asarray "Defined by craft\elements\db\ElementQuery")                       | [boolean](http://php.net/language.types.boolean) – Whether to return each element as an array.
| [behaviors](https://www.yiiframework.com/doc/api/2.0/yii-base-component#$behaviors-detail "Defined by yii\base\Component")                                | [yii\base\Behavior](https://www.yiiframework.com/doc/api/2.0/yii-base-behavior) – List of behaviors attached to this component
| [cachedResult](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#cachedresult "Defined by craft\elements\db\ElementQuery")             | [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – $elements The resulting elements, or null if setCachedResult() was never called or the criteria has changed
| [contentTable](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#contenttable "Defined by craft\elements\db\ElementQuery")             | [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – The content table that will be joined by this query.
| [criteria](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#criteria "Defined by craft\elements\db\ElementQuery")                     | [array](http://php.net/language.types.array)
| [customFields](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#customfields "Defined by craft\elements\db\ElementQuery")             | [craft\base\FieldInterface](https://docs.craftcms.com/api/v3/craft-base-fieldinterface.html), [null](http://php.net/language.types.null) – The fields that may be involved in this query.
| [dateCreated](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#datecreated "Defined by craft\elements\db\ElementQuery")               | `mixed` – When the resulting elements must have been created.
| [dateUpdated](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#dateupdated "Defined by craft\elements\db\ElementQuery")               | `mixed` – When the resulting elements must have been last updated.
| [descendantDist](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#descendantdist "Defined by craft\elements\db\ElementQuery")         | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – The maximum number of levels that results may be separated from [descendantOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-descendantof).
| [descendantOf](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#descendantof "Defined by craft\elements\db\ElementQuery")             | [integer](http://php.net/language.types.integer), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element (or its ID) that results must be a descendant of.
| [distinct](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$distinct-detail "Defined by yii\db\Query")                                              | [boolean](http://php.net/language.types.boolean) – Whether to select distinct rows of data only.
| [draftCreator](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#draftcreator "Defined by craft\elements\db\ElementQuery")             | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – The drafts’ creator ID
| [draftId](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#draftid "Defined by craft\elements\db\ElementQuery")                       | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – The ID of the draft to return (from the `drafts` table)
| [draftOf](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#draftof "Defined by craft\elements\db\ElementQuery")                       | [integer](http://php.net/language.types.integer), [false](http://php.net/language.types.boolean), [null](http://php.net/language.types.null) – The source element ID that drafts should be returned for.
| [drafts](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#drafts "Defined by craft\elements\db\ElementQuery")                         | [boolean](http://php.net/language.types.boolean) – Whether draft elements should be returned.
| [editable](craft-commerce-elements-db-variantquery.md#editable)                                                                                           | [boolean](http://php.net/language.types.boolean) – Whether to only return variants that the user has permission to edit.
| [elementType](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#elementtype "Defined by craft\elements\db\ElementQuery")               | [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – The name of the [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html) class.
| [emulateExecution](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#$emulateExecution-detail "Defined by yii\db\QueryTrait")                    | [boolean](http://php.net/language.types.boolean) – Whether to emulate the actual query execution, returning empty or false results.
| [enabledForSite](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#enabledforsite "Defined by craft\elements\db\ElementQuery")         | [boolean](http://php.net/language.types.boolean) – Whether the elements must be enabled for the chosen site.
| [fixedOrder](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#fixedorder "Defined by craft\elements\db\ElementQuery")                 | [boolean](http://php.net/language.types.boolean) – Whether results should be returned in the order specified by [id()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-id).
| [from](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$from-detail "Defined by yii\db\Query")                                                      | [array](http://php.net/language.types.array) – The table(s) to be selected from.
| [groupBy](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$groupBy-detail "Defined by yii\db\Query")                                                | [array](http://php.net/language.types.array) – How to group the query results.
| [hasDescendants](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#hasdescendants "Defined by craft\elements\db\ElementQuery")         | [boolean](http://php.net/language.types.boolean), [null](http://php.net/language.types.null) – Whether the resulting elements must have descendants.
| [hasProduct](craft-commerce-elements-db-variantquery.md#hasproduct)                                                                                       | [craft\commerce\elements\db\ProductQuery](craft-commerce-elements-db-productquery.md), [array](http://php.net/language.types.array) – Only return variants that match the resulting product query.
| [hasSales](craft-commerce-elements-db-variantquery.md#hassales)                                                                                           |
| [hasStock](craft-commerce-elements-db-variantquery.md#hasstock)                                                                                           |
| [having](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$having-detail "Defined by yii\db\Query")                                                  | [string](http://php.net/language.types.string), [array](http://php.net/language.types.array), [yii\db\ExpressionInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-expressioninterface) – The condition to be applied in the GROUP BY clause.
| [id](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#id "Defined by craft\elements\db\ElementQuery")                                 | [integer](http://php.net/language.types.integer), [integer](http://php.net/language.types.integer)[], [false](http://php.net/language.types.boolean), [null](http://php.net/language.types.null) – The element ID(s).
| [ignorePlaceholders](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#ignoreplaceholders "Defined by craft\elements\db\ElementQuery") | [boolean](http://php.net/language.types.boolean) – Whether to ignore placeholder elements when populating the results.
| [inReverse](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#inreverse "Defined by craft\elements\db\ElementQuery")                   | [boolean](http://php.net/language.types.boolean) – Whether the results should be queried in reverse.
| [indexBy](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#$indexBy-detail "Defined by yii\db\QueryTrait")                                      | [string](http://php.net/language.types.string), [callable](http://php.net/language.types.callable) – The name of the column by which the query results should be indexed by.
| [isDefault](craft-commerce-elements-db-variantquery.md#isdefault)                                                                                         |
| [iterator](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#iterator "Defined by craft\elements\db\ElementQuery")                     | [ArrayIterator](http://php.net/class.arrayiterator)
| [join](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$join-detail "Defined by yii\db\Query")                                                      | [array](http://php.net/language.types.array) – How to join with other tables.
| [leaves](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#leaves "Defined by craft\elements\db\ElementQuery")                         | [boolean](http://php.net/language.types.boolean) – Whether the elements must be “leaves” in the structure.
| [level](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#level "Defined by craft\elements\db\ElementQuery")                           | `mixed` – The element’s level within the structure
| [limit](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#$limit-detail "Defined by yii\db\QueryTrait")                                          | [integer](http://php.net/language.types.integer), [yii\db\ExpressionInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-expressioninterface) – Maximum number of records to be returned.
| [maxQty](craft-commerce-elements-db-variantquery.md#maxqty)                                                                                               |
| [minQty](craft-commerce-elements-db-variantquery.md#minqty)                                                                                               |
| [nextSiblingOf](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#nextsiblingof "Defined by craft\elements\db\ElementQuery")           | [integer](http://php.net/language.types.integer), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element (or its ID) that the result must be the next sibling of.
| [offset](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#$offset-detail "Defined by yii\db\QueryTrait")                                        | [integer](http://php.net/language.types.integer), [yii\db\ExpressionInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-expressioninterface) – Zero-based offset from where the records are to be returned.
| [orderBy](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#$orderBy-detail "Defined by yii\db\QueryTrait")                                      | [array](http://php.net/language.types.array) – How to sort the query results.
| [params](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$params-detail "Defined by yii\db\Query")                                                  | [array](http://php.net/language.types.array) – List of query parameter values indexed by parameter placeholders.
| [positionedAfter](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#positionedafter "Defined by craft\elements\db\ElementQuery")       | [integer](http://php.net/language.types.integer), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element (or its ID) that the results must be positioned after.
| [positionedBefore](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#positionedbefore "Defined by craft\elements\db\ElementQuery")     | [integer](http://php.net/language.types.integer), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element (or its ID) that the results must be positioned before.
| [preferSites](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#prefersites "Defined by craft\elements\db\ElementQuery")               | [array](http://php.net/language.types.array), [null](http://php.net/language.types.null) – Determines which site should be selected when querying multi-site elements.
| [prevSiblingOf](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#prevsiblingof "Defined by craft\elements\db\ElementQuery")           | [integer](http://php.net/language.types.integer), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element (or its ID) that the result must be the previous sibling of.
| [price](craft-commerce-elements-db-variantquery.md#price)                                                                                                 |
| [product](craft-commerce-elements-db-variantquery.md#product)                                                                                             | [craft\commerce\elements\Product](craft-commerce-elements-product.md)
| [productId](craft-commerce-elements-db-variantquery.md#productid)                                                                                         |
| [query](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#query "Defined by craft\elements\db\ElementQuery")                           | [craft\db\Query](https://docs.craftcms.com/api/v3/craft-db-query.html), [null](http://php.net/language.types.null) – The query object created by [prepare()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-prepare)
| [queryCacheDependency](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$queryCacheDependency-detail "Defined by yii\db\Query")                      | [yii\caching\Dependency](https://www.yiiframework.com/doc/api/2.0/yii-caching-dependency) – The dependency to be associated with the cached query result for this query
| [queryCacheDuration](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$queryCacheDuration-detail "Defined by yii\db\Query")                          | [integer](http://php.net/language.types.integer), [true](http://php.net/language.types.boolean) – The default number of seconds that query results can remain valid in cache.
| [rawSql](https://docs.craftcms.com/api/v3/craft-db-query.html#rawsql "Defined by craft\db\Query")                                                         | [string](http://php.net/language.types.string)
| [ref](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#ref "Defined by craft\elements\db\ElementQuery")                               | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null) – The reference code(s) used to identify the element(s).
| [relatedTo](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#relatedto "Defined by craft\elements\db\ElementQuery")                   | [integer](http://php.net/language.types.integer), [array](http://php.net/language.types.array), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element relation criteria.
| [revisionCreator](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#revisioncreator "Defined by craft\elements\db\ElementQuery")       | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – The revisions’ creator ID
| [revisionId](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#revisionid "Defined by craft\elements\db\ElementQuery")                 | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – The ID of the revision to return (from the `revisions` table)
| [revisionOf](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#revisionof "Defined by craft\elements\db\ElementQuery")                 | [integer](http://php.net/language.types.integer), [null](http://php.net/language.types.null) – The source element ID that revisions should be returned for
| [revisions](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#revisions "Defined by craft\elements\db\ElementQuery")                   | [boolean](http://php.net/language.types.boolean) – Whether revision elements should be returned.
| [search](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#search "Defined by craft\elements\db\ElementQuery")                         | [string](http://php.net/language.types.string), [array](http://php.net/language.types.array), [craft\search\SearchQuery](https://docs.craftcms.com/api/v3/craft-search-searchquery.html), [null](http://php.net/language.types.null) – The search term to filter the resulting elements by.
| [select](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$select-detail "Defined by yii\db\Query")                                                  | [array](http://php.net/language.types.array) – The columns being selected.
| [selectOption](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$selectOption-detail "Defined by yii\db\Query")                                      | [string](http://php.net/language.types.string) – Additional option that should be appended to the 'SELECT' keyword.
| [siblingOf](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#siblingof "Defined by craft\elements\db\ElementQuery")                   | [integer](http://php.net/language.types.integer), [craft\base\ElementInterface](https://docs.craftcms.com/api/v3/craft-base-elementinterface.html), [null](http://php.net/language.types.null) – The element (or its ID) that the results must be a sibling of.
| [siteId](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#siteid "Defined by craft\elements\db\ElementQuery")                         | [integer](http://php.net/language.types.integer), [integer](http://php.net/language.types.integer)[], [string](http://php.net/language.types.string), [null](http://php.net/language.types.null) – The site ID(s) that the elements should be returned in, or `'*'` if elements should be returned in all supported sites.
| [sku](craft-commerce-elements-db-variantquery.md#sku)                                                                                                     | [string](http://php.net/language.types.string) – The SKU of the variant
| [slug](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#slug "Defined by craft\elements\db\ElementQuery")                             | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null) – The slug that resulting elements must have.
| [status](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#status "Defined by craft\elements\db\ElementQuery")                         | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null) – The status(es) that the resulting elements must have.
| [stock](craft-commerce-elements-db-variantquery.md#stock)                                                                                                 |
| [structureId](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#structureid "Defined by craft\elements\db\ElementQuery")               | [integer](http://php.net/language.types.integer), [false](http://php.net/language.types.boolean), [null](http://php.net/language.types.null) – The structure ID that should be used to join in the structureelements table.
| [subQuery](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#subquery "Defined by craft\elements\db\ElementQuery")                     | [craft\db\Query](https://docs.craftcms.com/api/v3/craft-db-query.html), [null](http://php.net/language.types.null) – The subselect’s query object created by [prepare()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-prepare)
| [tablesUsedInFrom](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$tablesUsedInFrom-detail "Defined by yii\db\Query")                              | [string](http://php.net/language.types.string)[] – Table names indexed by aliases
| [title](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#title "Defined by craft\elements\db\ElementQuery")                           | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null) – The title that resulting elements must have.
| [trashed](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#trashed "Defined by craft\elements\db\ElementQuery")                       | [boolean](http://php.net/language.types.boolean), [null](http://php.net/language.types.null) – Whether to return trashed (soft-deleted) elements.
| [typeId](craft-commerce-elements-db-variantquery.md#typeid)                                                                                               |
| [uid](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#uid "Defined by craft\elements\db\ElementQuery")                               | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null) – The element UID(s).
| [union](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$union-detail "Defined by yii\db\Query")                                                    | [array](http://php.net/language.types.array) – This is used to construct the UNION clause(s) in a SQL statement.
| [unique](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#unique "Defined by craft\elements\db\ElementQuery")                         | [boolean](http://php.net/language.types.boolean) – Whether only elements with unique IDs should be returned by the query.
| [uri](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#uri "Defined by craft\elements\db\ElementQuery")                               | [string](http://php.net/language.types.string), [string](http://php.net/language.types.string)[], [null](http://php.net/language.types.null) – The URI that the resulting element must have.
| [where](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#$where-detail "Defined by yii\db\QueryTrait")                                          | [string](http://php.net/language.types.string), [array](http://php.net/language.types.array), [yii\db\ExpressionInterface](https://www.yiiframework.com/doc/api/2.0/yii-db-expressioninterface) – Query condition.
| [with](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#with "Defined by craft\elements\db\ElementQuery")                             | [string](http://php.net/language.types.string), [array](http://php.net/language.types.array), [null](http://php.net/language.types.null) – The eager-loading declaration.
| [withQueries](https://www.yiiframework.com/doc/api/2.0/yii-db-query#$withQueries-detail "Defined by yii\db\Query")                                        | [array](http://php.net/language.types.array) – This is used to construct the WITH section in a SQL query.
| [withStructure](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#withstructure "Defined by craft\elements\db\ElementQuery")           | [boolean](http://php.net/language.types.boolean), [null](http://php.net/language.types.null) – Whether element structure data should automatically be left-joined into the query.

### `editable`



Type

:   [boolean](http://php.net/language.types.boolean)



Whether to only return variants that the user has permission to edit.



[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L51)



### `hasProduct`



Type

:   [craft\commerce\elements\db\ProductQuery](craft-commerce-elements-db-productquery.md), [array](http://php.net/language.types.array)



Only return variants that match the resulting product query.



[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L96)



### `hasSales`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L91)



### `hasStock`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L81)



### `isDefault`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L71)



### `maxQty`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L111)



### `minQty`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L106)



### `price`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L86)



### `product`



Type

:   [craft\commerce\elements\Product](craft-commerce-elements-product.md)







[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L56)



### `productId`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L61)



### `sku`



Type

:   [string](http://php.net/language.types.string)



The SKU of the variant



[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L46)



### `stock`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L76)



### `typeId`









[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L66)





## Protected Properties

| Property                                                                    | Description
| --------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [defaultOrderBy](craft-commerce-elements-db-variantquery.md#defaultorderby) | [array](http://php.net/language.types.array) – The default [orderBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#orderBy()-detail) value to use if [orderBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#orderBy()-detail) is empty but not null.

### `defaultOrderBy`



Type

:   [array](http://php.net/language.types.array)





The default [orderBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#orderBy()-detail) value to use if [orderBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#orderBy()-detail) is empty but not null.





[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L101)





## Public Methods

| Method                                                                                                                                                             | Description
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [__call()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-__call "Defined by craft\elements\db\ElementQuery")                         | Calls the named method which is not a class method.
| [__clone()](https://docs.craftcms.com/api/v3/craft-base-clonefixtrait.html#method-__clone "Defined by craft\base\ClonefixTrait")                                   |
| [__construct()](craft-commerce-elements-db-variantquery.md#method-construct)                                                                                       | Constructor
| [__get()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-__get "Defined by craft\elements\db\ElementQuery")                           | Returns the value of a component property.
| [__isset()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-__isset "Defined by craft\elements\db\ElementQuery")                       | Checks if a property is set, i.e. defined and not null.
| [__set()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-__set "Defined by craft\elements\db\ElementQuery")                           | Sets the value of a component property.
| [__toString()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#__toString()-detail "Defined by yii\db\Query")                                                | Returns the SQL representation of Query
| [__unset()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#__unset()-detail "Defined by yii\base\Component")                                          | Sets a component property to be null.
| [addGroupBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#addGroupBy()-detail "Defined by yii\db\Query")                                                | Adds additional group-by columns to the existing ones.
| [addOrderBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#addOrderBy()-detail "Defined by yii\db\QueryTrait")                                      | Adds additional ORDER BY columns to the query.
| [addParams()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#addParams()-detail "Defined by yii\db\Query")                                                  | Adds additional parameters to be bound to the query.
| [addSelect()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#addSelect()-detail "Defined by yii\db\Query")                                                  | Add more columns to the SELECT part of the query.
| [all()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-all "Defined by craft\elements\db\ElementQuery")                               | Executes the query and returns all results as an array.
| [ancestorDist()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-ancestordist "Defined by craft\elements\db\ElementQuery")             | Narrows the query results to only {elements} that are up to a certain distance away from the {element} specified by [ancestorOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-ancestorof).
| [ancestorOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-ancestorof "Defined by craft\elements\db\ElementQuery")                 | Narrows the query results to only {elements} that are ancestors of another {element}.
| [andFilterCompare()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#andFilterCompare()-detail "Defined by yii\db\Query")                                    | Adds a filtering condition for a specific column and allow the user to choose a filter operator.
| [andFilterHaving()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#andFilterHaving()-detail "Defined by yii\db\Query")                                      | Adds an additional HAVING condition to the existing one but ignores [empty operands](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail).
| [andFilterWhere()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#andFilterWhere()-detail "Defined by yii\db\QueryTrait")                              | Adds an additional WHERE condition to the existing one but ignores [empty operands](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail).
| [andHaving()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#andHaving()-detail "Defined by yii\db\Query")                                                  | Adds an additional HAVING condition to the existing one.
| [andWhere()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#andWhere()-detail "Defined by yii\db\QueryTrait")                                          | Adds an additional WHERE condition to the existing one.
| [andWith()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-andwith "Defined by craft\elements\db\ElementQuery")                       | Causes the query to return matching {elements} eager-loaded with related elements, in addition to the elements that were already specified by [with()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-with).
| [anyStatus()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-anystatus "Defined by craft\elements\db\ElementQuery")                   | Clears out the [status()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-status) and [enabledForSite()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-enabledforsite) parameters.
| [archived()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-archived "Defined by craft\elements\db\ElementQuery")                     | Sets the [archived](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#archived) property.
| [asArray()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-asarray "Defined by craft\elements\db\ElementQuery")                       | Causes the query to return matching {elements} as arrays of data, rather than [[{element-class}]] objects.
| [attachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehavior()-detail "Defined by yii\base\Component")                            | Attaches a behavior to this component.
| [attachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#attachBehaviors()-detail "Defined by yii\base\Component")                          | Attaches a list of behaviors to the component.
| [average()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#average()-detail "Defined by yii\db\Query")                                                      | Returns the average of the specified column values.
| [batch()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#batch()-detail "Defined by yii\db\Query")                                                          | Starts a batch query.
| [behaviors()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-behaviors "Defined by craft\elements\db\ElementQuery")                   | Returns a list of behaviors that this component should behave as.
| [cache()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#cache()-detail "Defined by yii\db\Query")                                                          | Enables query cache for this Query.
| [canGetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canGetProperty()-detail "Defined by yii\base\Component")                            | Returns a value indicating whether a property can be read.
| [canSetProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#canSetProperty()-detail "Defined by yii\base\Component")                            | Returns a value indicating whether a property can be set.
| [className()](https://www.yiiframework.com/doc/api/2.0/yii-base-baseobject#className()-detail "Defined by yii\base\BaseObject")                                    | Returns the fully qualified name of this class.
| [clearCachedResult()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-clearcachedresult "Defined by craft\elements\db\ElementQuery")   | Clears the cached result.
| [column()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-column "Defined by craft\elements\db\ElementQuery")                         | Executes the query and returns the first column of the result.
| [count()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-count "Defined by craft\elements\db\ElementQuery")                           | Returns the number of records.
| [create()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#create()-detail "Defined by yii\db\Query")                                                        | Creates a new Query object and copies its property values from an existing one.
| [createCommand()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#createCommand()-detail "Defined by yii\db\Query")                                          | Creates a DB command that can be used to execute this query.
| [criteriaAttributes()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-criteriaattributes "Defined by craft\elements\db\ElementQuery") | Returns the query's criteria attributes.
| [dateCreated()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-datecreated "Defined by craft\elements\db\ElementQuery")               | Narrows the query results based on the {elements}’ creation dates.
| [dateUpdated()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-dateupdated "Defined by craft\elements\db\ElementQuery")               | Narrows the query results based on the {elements}’ last-updated dates.
| [descendantDist()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-descendantdist "Defined by craft\elements\db\ElementQuery")         | Narrows the query results to only {elements} that are up to a certain distance away from the {element} specified by [descendantOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-descendantof).
| [descendantOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-descendantof "Defined by craft\elements\db\ElementQuery")             | Narrows the query results to only {elements} that are descendants of another {element}.
| [detachBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehavior()-detail "Defined by yii\base\Component")                            | Detaches a behavior from the component.
| [detachBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#detachBehaviors()-detail "Defined by yii\base\Component")                          | Detaches all behaviors from the component.
| [distinct()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#distinct()-detail "Defined by yii\db\Query")                                                    | Sets the value indicating whether to SELECT DISTINCT or not.
| [draftCreator()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-draftcreator "Defined by craft\elements\db\ElementQuery")             | Narrows the query results to only drafts created by a given user.
| [draftId()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-draftid "Defined by craft\elements\db\ElementQuery")                       | Narrows the query results based on the {elements}’ draft’s ID (from the `drafts` table).
| [draftOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-draftof "Defined by craft\elements\db\ElementQuery")                       | Narrows the query results to only drafts of a given {element}.
| [drafts()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-drafts "Defined by craft\elements\db\ElementQuery")                         | Narrows the query results to only drafts {elements}.
| [each()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#each()-detail "Defined by yii\db\Query")                                                            | Starts a batch query and retrieves data row by row.
| [emulateExecution()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#emulateExecution()-detail "Defined by yii\db\QueryTrait")                          | Sets whether to emulate query execution, preventing any interaction with data storage.
| [enabledForSite()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-enabledforsite "Defined by craft\elements\db\ElementQuery")         | Narrows the query results based on whether the {elements} are enabled in the site they’re being queried in, per the [site()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-site) parameter.
| [ensureBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#ensureBehaviors()-detail "Defined by yii\base\Component")                          | Makes sure that the behaviors declared in [behaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#behaviors()-detail) are attached to this component.
| [exists()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-exists "Defined by craft\elements\db\ElementQuery")                         | Returns a value indicating whether the query result contains any row of data.
| [extraFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extraFields()-detail "Defined by yii\base\ArrayableTrait")                        | Returns the list of fields that can be expanded further and returned by [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail).
| [fields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#fields()-detail "Defined by yii\base\ArrayableTrait")                                  | Returns the list of fields that should be returned by default by [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail) when no specific fields are specified.
| [filterHaving()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#filterHaving()-detail "Defined by yii\db\Query")                                            | Sets the HAVING part of the query but ignores [empty operands](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail).
| [filterWhere()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#filterWhere()-detail "Defined by yii\db\QueryTrait")                                    | Sets the WHERE part of the query but ignores [empty operands](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail).
| [find()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-find "Defined by craft\elements\db\ElementQuery")                             | Returns all elements that match the criteria.
| [first()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-first "Defined by craft\elements\db\ElementQuery")                           | Returns the first element that matches the criteria.
| [fixedOrder()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-fixedorder "Defined by craft\elements\db\ElementQuery")                 | Causes the query results to be returned in the order specified by [id()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-id).
| [from()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#from()-detail "Defined by yii\db\Query")                                                            | Sets the FROM part of the query.
| [getBehavior()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehavior()-detail "Defined by yii\base\Component")                                  | Returns the named behavior object.
| [getBehaviors()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#getBehaviors()-detail "Defined by yii\base\Component")                                | Returns all behaviors attached to this component.
| [getCachedResult()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-getcachedresult "Defined by craft\elements\db\ElementQuery")       | Returns the resulting elements set by [setCachedResult()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-setcachedresult), if the criteria params haven’t changed since then.
| [getCriteria()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-getcriteria "Defined by craft\elements\db\ElementQuery")               | Returns an array of the current criteria attribute values.
| [getIterator()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-getiterator "Defined by craft\elements\db\ElementQuery")               | Required by the IteratorAggregate interface.
| [getRawSql()](https://docs.craftcms.com/api/v3/craft-db-query.html#method-getrawsql "Defined by craft\db\Query")                                                   | Shortcut for `createCommand()->getRawSql()`.
| [getTablesUsedInFrom()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#getTablesUsedInFrom()-detail "Defined by yii\db\Query")                              | Returns table names used in [from()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#from()-detail) indexed by aliases.
| [groupBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#groupBy()-detail "Defined by yii\db\Query")                                                      | Sets the GROUP BY part of the query.
| [hasDescendants()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-hasdescendants "Defined by craft\elements\db\ElementQuery")         | Narrows the query results based on whether the {elements} have any descendants.
| [hasEventHandlers()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasEventHandlers()-detail "Defined by yii\base\Component")                        | Returns a value indicating whether there is any handler attached to the named event.
| [hasMethod()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasMethod()-detail "Defined by yii\base\Component")                                      | Returns a value indicating whether a method is defined.
| [hasProduct()](craft-commerce-elements-db-variantquery.md#method-hasproduct)                                                                                       | Narrows the query results to only variants for certain products.
| [hasProperty()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#hasProperty()-detail "Defined by yii\base\Component")                                  | Returns a value indicating whether a property is defined for this component.
| [hasSales()](craft-commerce-elements-db-variantquery.md#method-hassales)                                                                                           | Narrows the query results to only variants that are on sale.
| [hasStock()](craft-commerce-elements-db-variantquery.md#method-hasstock)                                                                                           | Narrows the query results to only variants that have stock.
| [having()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#having()-detail "Defined by yii\db\Query")                                                        | Sets the HAVING part of the query.
| [id()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-id "Defined by craft\elements\db\ElementQuery")                                 | Narrows the query results based on the {elements}’ IDs.
| [ids()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-ids "Defined by craft\elements\db\ElementQuery")                               | Executes the query and returns the IDs of the resulting elements.
| [ignorePlaceholders()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-ignoreplaceholders "Defined by craft\elements\db\ElementQuery") | Causes the query to return matching {elements} as they are stored in the database, ignoring matching placeholder elements that were set by [craft\services\Elements::setPlaceholderElement()](https://docs.craftcms.com/api/v3/craft-services-elements.html#method-setplaceholderelement).
| [inReverse()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-inreverse "Defined by craft\elements\db\ElementQuery")                   | Causes the query results to be returned in reverse order.
| [indexBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#indexBy()-detail "Defined by yii\db\QueryTrait")                                            | Sets the [indexBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#indexBy()-detail) property.
| [init()](https://docs.craftcms.com/api/v3/craft-db-query.html#method-init "Defined by craft\db\Query")                                                             | Initializes the object.
| [innerJoin()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#innerJoin()-detail "Defined by yii\db\Query")                                                  | Appends an INNER JOIN part to the query.
| [isDefault()](craft-commerce-elements-db-variantquery.md#method-isdefault)                                                                                         | Narrows the query results to only default variants.
| [isJoined()](https://docs.craftcms.com/api/v3/craft-db-query.html#method-isjoined "Defined by craft\db\Query")                                                     | Returns whether a given table has been joined in this query.
| [join()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#join()-detail "Defined by yii\db\Query")                                                            | Appends a JOIN part to the query.
| [last()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-last "Defined by craft\elements\db\ElementQuery")                             | Returns the last element that matches the criteria.
| [leaves()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-leaves "Defined by craft\elements\db\ElementQuery")                         | Narrows the query results based on whether the {elements} are “leaves” ({elements} with no descendants).
| [leftJoin()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#leftJoin()-detail "Defined by yii\db\Query")                                                    | Appends a LEFT OUTER JOIN part to the query.
| [level()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-level "Defined by craft\elements\db\ElementQuery")                           | Narrows the query results based on the {elements}’ level within the structure.
| [limit()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#limit()-detail "Defined by yii\db\QueryTrait")                                                | Determines the number of {elements} that should be returned.
| [locale()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-locale "Defined by craft\elements\db\ElementQuery")                         | Sets the `\craft\elements\db\$site` property.
| [localeEnabled()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-localeenabled "Defined by craft\elements\db\ElementQuery")           | Sets the [enabledForSite](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#enabledforsite) property.
| [max()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#max()-detail "Defined by yii\db\Query")                                                              | Returns the maximum of the specified column values.
| [maxQty()](craft-commerce-elements-db-variantquery.md#method-maxqty)                                                                                               | Narrows the query results based on the variants’ max quantity.
| [min()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#min()-detail "Defined by yii\db\Query")                                                              | Returns the minimum of the specified column values.
| [minQty()](craft-commerce-elements-db-variantquery.md#method-minqty)                                                                                               | Narrows the query results based on the variants’ min quantity.
| [nextSiblingOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-nextsiblingof "Defined by craft\elements\db\ElementQuery")           | Narrows the query results to only the {element} that comes immediately after another {element}.
| [noCache()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#noCache()-detail "Defined by yii\db\Query")                                                      | Disables query cache for this Query.
| [nth()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-nth "Defined by craft\elements\db\ElementQuery")                               | Executes the query and returns a single row of result at a given offset.
| [off()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#off()-detail "Defined by yii\base\Component")                                                  | Detaches an existing event handler from this component.
| [offset()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#offset()-detail "Defined by yii\db\QueryTrait")                                              | Determines how many {elements} should be skipped in the results.
| [offsetExists()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-offsetexists "Defined by craft\elements\db\ElementQuery")             | Required by the ArrayAccess interface.
| [offsetGet()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-offsetget "Defined by craft\elements\db\ElementQuery")                   | Required by the ArrayAccess interface.
| [offsetSet()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-offsetset "Defined by craft\elements\db\ElementQuery")                   | Required by the ArrayAccess interface.
| [offsetUnset()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-offsetunset "Defined by craft\elements\db\ElementQuery")               | Required by the ArrayAccess interface.
| [on()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#on()-detail "Defined by yii\base\Component")                                                    | Attaches an event handler to an event.
| [one()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-one "Defined by craft\elements\db\ElementQuery")                               | Executes the query and returns a single row of result.
| [orFilterHaving()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#orFilterHaving()-detail "Defined by yii\db\Query")                                        | Adds an additional HAVING condition to the existing one but ignores [empty operands](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail).
| [orFilterWhere()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#orFilterWhere()-detail "Defined by yii\db\QueryTrait")                                | Adds an additional WHERE condition to the existing one but ignores [empty operands](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail).
| [orHaving()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#orHaving()-detail "Defined by yii\db\Query")                                                    | Adds an additional HAVING condition to the existing one.
| [orWhere()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#orWhere()-detail "Defined by yii\db\QueryTrait")                                            | Adds an additional WHERE condition to the existing one.
| [order()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-order "Defined by craft\elements\db\ElementQuery")                           | Sets the [orderBy](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#orderby) property.
| [orderBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#orderBy()-detail "Defined by yii\db\QueryTrait")                                            | Determines the order that the {elements} should be returned in. (If empty, defaults to `{default-order-by}`.)
| [pairs()](https://docs.craftcms.com/api/v3/craft-db-query.html#method-pairs "Defined by craft\db\Query")                                                           | Executes the query and returns the first two columns in the results as key/value pairs.
| [params()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#params()-detail "Defined by yii\db\Query")                                                        | Sets the parameters to be bound to the query.
| [populate()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-populate "Defined by craft\elements\db\ElementQuery")                     | Converts the raw query results into the format as specified by this query.
| [positionedAfter()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-positionedafter "Defined by craft\elements\db\ElementQuery")       | Narrows the query results to only {elements} that are positioned after another {element}.
| [positionedBefore()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-positionedbefore "Defined by craft\elements\db\ElementQuery")     | Narrows the query results to only {elements} that are positioned before another {element}.
| [preferSites()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-prefersites "Defined by craft\elements\db\ElementQuery")               | If [unique()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-unique) is set, this determines which site should be selected when querying multi-site elements.
| [prepare()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-prepare "Defined by craft\elements\db\ElementQuery")                       | Prepares for building SQL.
| [prevSiblingOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-prevsiblingof "Defined by craft\elements\db\ElementQuery")           | Narrows the query results to only the {element} that comes immediately before another {element}.
| [price()](craft-commerce-elements-db-variantquery.md#method-price)                                                                                                 | Narrows the query results based on the variants’ price.
| [product()](craft-commerce-elements-db-variantquery.md#method-product)                                                                                             | Narrows the query results based on the variants’ product.
| [productId()](craft-commerce-elements-db-variantquery.md#method-productid)                                                                                         | Narrows the query results based on the variants’ products’ IDs.
| [ref()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-ref "Defined by craft\elements\db\ElementQuery")                               | Narrows the query results based on a reference string.
| [relatedTo()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-relatedto "Defined by craft\elements\db\ElementQuery")                   | Narrows the query results to only {elements} that are related to certain other elements.
| [revisionCreator()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-revisioncreator "Defined by craft\elements\db\ElementQuery")       | Narrows the query results to only revisions created by a given user.
| [revisionId()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-revisionid "Defined by craft\elements\db\ElementQuery")                 | Narrows the query results based on the {elements}’ revision’s ID (from the `revisions` table).
| [revisionOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-revisionof "Defined by craft\elements\db\ElementQuery")                 | Narrows the query results to only revisions of a given {element}.
| [revisions()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-revisions "Defined by craft\elements\db\ElementQuery")                   | Narrows the query results to only revision {elements}.
| [rightJoin()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#rightJoin()-detail "Defined by yii\db\Query")                                                  | Appends a RIGHT OUTER JOIN part to the query.
| [scalar()](https://docs.craftcms.com/api/v3/craft-db-query.html#method-scalar "Defined by craft\db\Query")                                                         | Returns the query result as a scalar value.
| [search()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-search "Defined by craft\elements\db\ElementQuery")                         | Narrows the query results to only {elements} that match a search query.
| [select()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#select()-detail "Defined by yii\db\Query")                                                        | Sets the SELECT part of the query.
| [setCachedResult()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-setcachedresult "Defined by craft\elements\db\ElementQuery")       | Sets the resulting elements.
| [siblingOf()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-siblingof "Defined by craft\elements\db\ElementQuery")                   | Narrows the query results to only {elements} that are siblings of another {element}.
| [site()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-site "Defined by craft\elements\db\ElementQuery")                             | Determines which site(s) the {elements} should be queried in.
| [siteId()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-siteid "Defined by craft\elements\db\ElementQuery")                         | Determines which site(s) the {elements} should be queried in, per the site’s ID.
| [sku()](craft-commerce-elements-db-variantquery.md#method-sku)                                                                                                     | Narrows the query results based on the {elements}’ SKUs.
| [slug()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-slug "Defined by craft\elements\db\ElementQuery")                             | Narrows the query results based on the {elements}’ slugs.
| [status()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-status "Defined by craft\elements\db\ElementQuery")                         | Narrows the query results based on the {elements}’ statuses.
| [stock()](craft-commerce-elements-db-variantquery.md#method-stock)                                                                                                 | Narrows the query results based on the variants’ stock.
| [structureId()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-structureid "Defined by craft\elements\db\ElementQuery")               | Determines which structure data should be joined into the query.
| [sum()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#sum()-detail "Defined by yii\db\Query")                                                              | Returns the sum of the specified column values.
| [title()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-title "Defined by craft\elements\db\ElementQuery")                           | Narrows the query results based on the {elements}’ titles.
| [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail "Defined by yii\base\ArrayableTrait")                                | Converts the model into an array.
| [total()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-total "Defined by craft\elements\db\ElementQuery")                           | Returns the total elements that match the criteria.
| [trashed()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-trashed "Defined by craft\elements\db\ElementQuery")                       | Narrows the query results to only {elements} that have been soft-deleted.
| [trigger()](https://www.yiiframework.com/doc/api/2.0/yii-base-component#trigger()-detail "Defined by yii\base\Component")                                          | Triggers an event.
| [typeId()](craft-commerce-elements-db-variantquery.md#method-typeid)                                                                                               | Narrows the query results based on the variants’ product types, per their IDs.
| [uid()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-uid "Defined by craft\elements\db\ElementQuery")                               | Narrows the query results based on the {elements}’ UIDs.
| [union()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#union()-detail "Defined by yii\db\Query")                                                          | Appends a SQL statement using UNION operator.
| [unique()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-unique "Defined by craft\elements\db\ElementQuery")                         | Determines whether only elements with unique IDs should be returned by the query.
| [uri()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-uri "Defined by craft\elements\db\ElementQuery")                               | Narrows the query results based on the {elements}’ URIs.
| [where()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#where()-detail "Defined by yii\db\QueryTrait")                                                | Sets the WHERE part of the query.
| [with()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-with "Defined by craft\elements\db\ElementQuery")                             | Causes the query to return matching {elements} eager-loaded with related elements.
| [withQuery()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#withQuery()-detail "Defined by yii\db\Query")                                                  | Prepends a SQL statement using WITH syntax.
| [withStructure()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-withstructure "Defined by craft\elements\db\ElementQuery")           | Explicitly determines whether the query should join in the structure data.

### `__construct()`





Constructor








[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L116-L124)


#### Arguments

- `$elementType` ([string](http://php.net/language.types.string)) – The element type class associated with this query
- `$config` ([array](http://php.net/language.types.array)) – Configurations to be applied to the newly created query object




### `hasProduct()`





Narrows the query results to only variants for certain products.

Possible values include:

| Value | Fetches {elements}…
| - | -
| a [ProductQuery](craft-commerce-elements-db-productquery.md) object | for products that match the query.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L348-L352)


#### Arguments

- `$value` ([craft\commerce\elements\db\ProductQuery](craft-commerce-elements-db-productquery.md), [array](http://php.net/language.types.array)) – The property value

#### Returns

`static` – Self reference



### `hasSales()`





Narrows the query results to only variants that are on sale.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `true` | on sale
| `false` | not on sale


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L330-L334)


#### Arguments

- `$value` ([boolean](http://php.net/language.types.boolean))

#### Returns

`static` – Self reference



### `hasStock()`





Narrows the query results to only variants that have stock.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `true` | with stock.
| `false` | with no stock.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L311-L315)


#### Arguments

- `$value` ([boolean](http://php.net/language.types.boolean))

#### Returns

`static` – Self reference



### `isDefault()`





Narrows the query results to only default variants.




[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L252-L256)


#### Arguments

- `$value` ([boolean](http://php.net/language.types.boolean)) – The property value

#### Returns

`static` – Self reference


---

#### Example

::: code
```twig
{# Fetch default variants #}
{% set {elements-var} = {twig-function}
    .isDefault()
    .all() %}
```

```php
// Fetch default variants
${elements-var} = {element-class}::find()
    ->isDefault()
    ->all();
```
:::


### `maxQty()`





Narrows the query results based on the variants’ max quantity.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `100` | with a maxQty of 100.
| `'>= 100'` | with a maxQty of at least 100.
| `'< 100'` | with a maxQty of less than 100.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L388-L392)


#### Arguments

- `$value` (`mixed`) – The property value

#### Returns

`static` – Self reference



### `minQty()`





Narrows the query results based on the variants’ min quantity.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `100` | with a minQty of 100.
| `'>= 100'` | with a minQty of at least 100.
| `'< 100'` | with a minQty of less than 100.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L368-L372)


#### Arguments

- `$value` (`mixed`) – The property value

#### Returns

`static` – Self reference



### `price()`





Narrows the query results based on the variants’ price.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `100` | with a price of 100.
| `'>= 100'` | with a price of at least 100.
| `'< 100'` | with a price of less than 100.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L292-L296)


#### Arguments

- `$value` (`mixed`) – The property value

#### Returns

`static` – Self reference



### `product()`





Narrows the query results based on the variants’ product.

Possible values include:

| Value | Fetches {elements}…
| - | -
| a [Product](craft-commerce-elements-product.md) object | for a product represented by the object.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L184-L188)


#### Arguments

- `$value` (`mixed`)

#### Returns

`static` – Self reference



### `productId()`





Narrows the query results based on the variants’ products’ IDs.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `1` | for a product with an ID of 1.
| `[1, 2]` | for product with an ID of 1 or 2.
| `['not', 1, 2]` | for product not with an ID of 1 or 2.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L204-L208)


#### Arguments

- `$value` (`mixed`)

#### Returns

`static` – Self reference



### `sku()`





Narrows the query results based on the {elements}’ SKUs.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `'foo'` | with a SKU of `foo`.
| `'foo*'` | with a SKU that begins with `foo`.
| `'*foo'` | with a SKU that ends with `foo`.
| `'*foo*'` | with a SKU that contains `foo`.
| `'not *foo*'` | with a SKU that doesn’t contain `foo`.
| `['*foo*', '*bar*'` | with a SKU that contains `foo` or `bar`.
| `['not', '*foo*', '*bar*']` | with a SKU that doesn’t contain `foo` or `bar`.




[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L166-L170)


#### Arguments

- `$value` (`mixed`)

#### Returns

`static` – Self reference


---

#### Example

::: code
```twig
{# Get the requested {element} SKU from the URL #}
{% set requestedSlug = craft.app.request.getSegment(3) %}

{# Fetch the {element} with that slug #}
{% set {element-var} = {twig-method}
    .sku(requestedSlug|literal)
    .one() %}
```

```php
// Get the requested {element} SKU from the URL
$requestedSlug = \Craft::$app->request->getSegment(3);

// Fetch the {element} with that slug
${element-var} = {php-method}
    ->sku(\craft\helpers\Db::escapeParam($requestedSlug))
    ->one();
```
:::


### `stock()`





Narrows the query results based on the variants’ stock.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `0` | with no stock.
| `'>= 5'` | with a stock of at least 5.
| `'< 10'` | with a stock of less than 10.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L272-L276)


#### Arguments

- `$value` (`mixed`) – The property value

#### Returns

`static` – Self reference



### `typeId()`





Narrows the query results based on the variants’ product types, per their IDs.

Possible values include:

| Value | Fetches {elements}…
| - | -
| `1` | for a product of a type with an ID of 1.
| `[1, 2]` | for product of a type with an ID of 1 or 2.
| `['not', 1, 2]` | for product of a type not with an ID of 1 or 2.


[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L224-L228)


#### Arguments

- `$value` (`mixed`)

#### Returns

`static` – Self reference





## Protected Methods

| Method                                                                                                                                                         | Description
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| [afterPrepare()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-afterprepare "Defined by craft\elements\db\ElementQuery")         | This method is called at the end of preparing an element query for the query builder.
| [beforePrepare()](craft-commerce-elements-db-variantquery.md#method-beforeprepare)                                                                             | This method is called at the beginning of preparing an element query for the query builder.
| [cleanUpTableNames()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#cleanUpTableNames()-detail "Defined by yii\db\Query")                              | Clean up table names and aliases Both aliases and names are enclosed into {{ and }}.
| [customFields()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-customfields "Defined by craft\elements\db\ElementQuery")         | Returns the fields that should take part in an upcoming elements query.
| [extractFieldsFor()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extractFieldsFor()-detail "Defined by yii\base\ArrayableTrait")          | Extract nested fields from a fields collection for a given root field Nested fields are separated with dots (.). e.g: "item.id" The previous example would extract "id".
| [extractRootFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#extractRootFields()-detail "Defined by yii\base\ArrayableTrait")        | Extracts the root field names from nested fields.
| [filterCondition()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#filterCondition()-detail "Defined by yii\db\QueryTrait")                        | Removes [empty operands](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail) from the given query condition.
| [getUnaliasedColumnsFromSelect()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#getUnaliasedColumnsFromSelect()-detail "Defined by yii\db\Query")      |
| [getUniqueColumns()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#getUniqueColumns()-detail "Defined by yii\db\Query")                                | Returns unique column names excluding duplicates.
| [isEmpty()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#isEmpty()-detail "Defined by yii\db\QueryTrait")                                        | Returns a value indicating whether the give value is "empty".
| [joinElementTable()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-joinelementtable "Defined by craft\elements\db\ElementQuery") | Joins in a table with an `id` column that has a foreign key pointing to `craft_elements`.`id`.
| [normalizeOrderBy()](https://www.yiiframework.com/doc/api/2.0/yii-db-querytrait#normalizeOrderBy()-detail "Defined by yii\db\QueryTrait")                      | Normalizes format of ORDER BY data.
| [normalizeSelect()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#normalizeSelect()-detail "Defined by yii\db\Query")                                  | Normalizes the SELECT columns passed to [select()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#select()-detail) or [addSelect()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#addSelect()-detail).
| [queryScalar()](https://docs.craftcms.com/api/v3/craft-db-query.html#method-queryscalar "Defined by craft\db\Query")                                           | Queries a scalar value by setting [select()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#select()-detail) first.
| [resolveFields()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#resolveFields()-detail "Defined by yii\base\ArrayableTrait")                | Determines which fields can be returned by [toArray()](https://www.yiiframework.com/doc/api/2.0/yii-base-arrayabletrait#toArray()-detail).
| [setCommandCache()](https://www.yiiframework.com/doc/api/2.0/yii-db-query#setCommandCache()-detail "Defined by yii\db\Query")                                  | Sets $command cache, if this query has enabled caching.
| [statusCondition()](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#method-statuscondition "Defined by craft\elements\db\ElementQuery")   | Returns the condition that should be applied to the element query for a given status.

### `beforePrepare()`





This method is called at the beginning of preparing an element query for the query builder.



The main Query object being prepared for the query builder is available via [query](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#query).
The subselect’s Query object being prepared is available via [subQuery](https://docs.craftcms.com/api/v3/craft-elements-db-elementquery.html#subquery).
The role of the subselect query is to apply conditions to the query and narrow the result set down to
just the elements that should actually be returned.
The role of the main query is to join in any tables that should be included in the results, and select
all of the columns that should be included in the results.




[View source](https://github.com/craftcms/commerce/blob/master/src/elements/db/VariantQuery.php#L397-L707)



#### Returns

[boolean](http://php.net/language.types.boolean) – Whether the query should be prepared and returned to the query builder.
If false, the query will be cancelled and no results will be returned.







