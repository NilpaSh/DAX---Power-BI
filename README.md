# DAX---Power-BI

Aggregation	

**APPROXIMATEDISTINCTCOUNT**	Returns an estimated count of unique values in a column.

**AVERAGE**	Returns the average (arithmetic mean) of all the numbers in a column.

**AVERAGEA**	Returns the average (arithmetic mean) of the values in a column.

**AVERAGEX**	Calculates the average (arithmetic mean) of a set of expressions evaluated over a table.

**COUNT**	Counts the number of rows in the specified column that contain non-blank values. Does not support Boolean values.

**COUNTA**	Counts the number of rows in the specified column that contain non-blank values. Supports Boolean values.

**COUNTAX**	Counts non-blank results when evaluating the result of an expression over a table.

**COUNTBLANK**	Counts the number of blank cells in a column.

**COUNTROWS**	Counts the number of rows in the specified table, or in a table defined by an expression.

**COUNTX**	Counts the number of rows that contain a number or an expression that evaluates to a number, when evaluating an expression over a table.

**DISTINCTCOUNT**	Counts the number of distinct values in a column.

**DISTINCTCOUNTNOBLANK**	Counts the number of distinct values in a column.

**MAX**	Returns the largest numeric value in a column, or between two scalar expressions.

**MAXA**	Returns the largest value in a column.

**MAXX**	Evaluates an expression for each row of a table and returns the largest numeric value.

**MIN**	Returns the smallest numeric value in a column, or between two scalar expressions.

**MINA**	Returns the smallest value in a column, including any logical values and numbers represented as text.

**MINX**	Returns the smallest numeric value that results from evaluating an expression for each row of a table.

**PRODUCT**	Returns the product of the numbers in a column.

**PRODUCTX**	Returns the product of an expression evaluated for each row in a table.

**SUM**	Adds all the numbers in a column.

**SUMX**	Returns the sum of an expression evaluated for each row in a table.

Date and Time function	
CALENDAR	Returns a table with a single column named "Date" that contains a contiguous set of dates.
CALENDARAUTO	Returns a table with a single column named "Date" that contains a contiguous set of dates.
DATE	Returns the specified date in datetime format.
DATEDIFF	Returns the number of interval boundaries between two dates.
DATEVALUE	Converts a date in the form of text to a date in datetime format.
DAY	Returns the day of the month, a number from 1 to 31.
EDATE	Returns the date that is the indicated number of months before or after the start date.
EOMONTH	Returns the date in datetime format of the last day of the month, before or after a specified number of months.
HOUR	Returns the hour as a number from 0 (12:00 A.M.) to 23 (11:00 P.M.).
MINUTE	Returns the minute as a number from 0 to 59, given a date and time value.
MONTH	Returns the month as a number from 1 (January) to 12 (December).
NETWORKDAYS	Returns the number of whole workdays between two dates.
NOW	Returns the current date and time in datetime format.
QUARTER	Returns the quarter as a number from 1 to 4.
SECOND	Returns the seconds of a time value, as a number from 0 to 59.
TIME	Converts hours, minutes, and seconds given as numbers to a time in datetime format.
TIMEVALUE	Converts a time in text format to a time in datetime format.
TODAY	Returns the current date.
UTCNOW	Returns the current UTC date and time
UTCTODAY	Returns the current UTC date.
WEEKDAY	Returns a number from 1 to 7 identifying the day of the week of a date.
WEEKNUM	Returns the week number for the given date and year according to the return_type value.
YEAR	Returns the year of a date as a four digit integer in the range 1900-9999.
YEARFRAC	Calculates the fraction of the year represented by the number of whole days between two dates.
Filter	
ALL	Returns all the rows in a table, or all the values in a column, ignoring any filters that might have been applied.
ALLCROSSFILTERED	Clear all filters which are applied to a table.
ALLEXCEPT	Removes all context filters in the table except filters that have been applied to the specified columns.
ALLNOBLANKROW	From the parent table of a relationship, returns all rows but the blank row, or all distinct values of a column but the blank row, and disregards any context filters that might exist.
ALLSELECTED	Removes context filters from columns and rows in the current query, while retaining all other context filters or explicit filters.
CALCULATE	Evaluates an expression in a modified filter context.
CALCULATETABLE	Evaluates a table expression in a modified filter context.
EARLIER	Returns the current value of the specified column in an outer evaluation pass of the mentioned column.
EARLIEST	Returns the current value of the specified column in an outer evaluation pass of the specified column.
FILTER	Returns a table that represents a subset of another table or expression.
FIRST	Used in visual calculations only. Retrieves a value in the visual matrix from the first row of an axis.
INDEX	Returns a row at an absolute position, specified by the position parameter, within the specified partition, sorted by the specified order or on the specified axis.
KEEPFILTERS	Modifies how filters are applied while evaluating a CALCULATE or CALCULATETABLE function.
LAST	Used in visual calculations only. Retrieves a value in the visual matrix from the last row of an axis.
LOOKUP	In visual calculation mode only. Look up the value when filters applied.
LOOKUPWITHTOTALS	In visual calculation mode only. Look up the value when filters applied. Filters not specified will not be inferred.
LOOKUPVALUE	Returns the value for the row that meets all criteria specified by search conditions. The function can apply one or more search conditions.
MATCHBY	In window functions, defines the columns that are used to determine how to match data and identify the current row.
MOVINGAVERAGE	Returns a moving average calculated along the given axis of the visual matrix.
NEXT	Used in visual calculations only. Retrieves a value in the next row of an axis in the visual matrix.
OFFSET	Returns a single row that is positioned either before or after the current row within the same table, by a given offset.
ORDERBY	Defines the columns that determine the sort order within each of a window function’s partitions.
PARTITIONBY	Defines the columns that are used to partition a window function’s relation parameter.
PREVIOUS	Used in visual calculations only. Retrieves a value in the previous row of an axis in the visual matrix.
RANGE	Returns an interval of rows within the given axis, relative to the current row. A shortcut for WINDOW.
RANK	Returns the ranking of a row within the given interval.
REMOVEFILTERS	Clears filters from the specified tables or columns.
ROWNUMBER	Returns the unique ranking of a row within the given interval.
RUNNINGSUM	Returns a running sum calculated along the given axis of the visual matrix.
SELECTEDVALUE	Returns the value when the context for columnName has been filtered down to one distinct value only. Otherwise returns alternateResult.
WINDOW	Returns multiple rows which are positioned within the given interval.
Financial	
ACCRINT	Returns the accrued interest for a security that pays periodic interest.
ACCRINTM	Returns the accrued interest for a security that pays interest at maturity.
AMORDEGRC	Returns the depreciation for each accounting period. Similar to AMORLINC, except a depreciation coefficient is applied depending on the life of the assets.
AMORLINC	Returns the depreciation for each accounting period.
COUPDAYBS	Returns the number of days from the beginning of a coupon period until its settlement date.
COUPDAYS	Returns the number of days in the coupon period that contains the settlement date.
COUPDAYSNC	Returns the number of days from the settlement date to the next coupon date.
COUPNCD	Returns the next coupon date after the settlement date.
COUPNUM	Returns the number of coupons payable between the settlement date and maturity date, rounded up to the nearest whole coupon.
COUPPCD	Returns the previous coupon date before the settlement date.
CUMIPMT	Returns the cumulative interest paid on a loan between start_period and end_period.
CUMPRINC	Returns the cumulative principal paid on a loan between start_period and end_period.
DB	Returns the depreciation of an asset for a specified period using the fixed-declining balance method.
DDB	Returns the depreciation of an asset for a specified period using the double-declining balance method or some other method you specify.
DISC	Returns the discount rate for a security.
DOLLARDE	Converts a dollar price expressed as an integer part and a fraction part, such as 1.02, into a dollar price expressed as a decimal number.
DOLLARFR	Converts a dollar price expressed as an integer part and a fraction part, such as 1.02, into a dollar price expressed as a decimal number.
DURATION	Returns the Macauley duration for an assumed par value of $100.
EFFECT	Returns the effective annual interest rate, given the nominal annual interest rate and the number of compounding periods per year.
FV	Calculates the future value of an investment based on a constant interest rate.
INTRATE	Returns the interest rate for a fully invested security.
IPMT	Returns the interest payment for a given period for an investment based on periodic, constant payments and a constant interest rate.
ISPMT	Calculates the interest paid (or received) for the specified period of a loan (or investment) with even principal payments.
MDURATION	Returns the modified Macauley duration for a security with an assumed par value of $100.
NOMINAL	Returns the nominal annual interest rate, given the effective rate and the number of compounding periods per year.
NPER	Returns the number of periods for an investment based on periodic, constant payments and a constant interest rate.
ODDFPRICE	Returns the price per $100 face value of a security having an odd (short or long) first period.
ODDFYIELD	Returns the yield of a security that has an odd (short or long) first period.
ODDLPRICE	Returns the price per $100 face value of a security having an odd (short or long) last coupon period.
ODDLYIELD	Returns the yield of a security that has an odd (short or long) last period.
PDURATION	Returns the number of periods required by an investment to reach a specified value.
PMT	Calculates the payment for a loan based on constant payments and a constant interest rate.
PPMT	Returns the payment on the principal for a given period for an investment based on periodic, constant payments and a constant interest rate.
PRICE	Returns the price per $100 face value of a security that pays periodic interest.
PRICEDISC	Returns the price per $100 face value of a discounted security.
PRICEMAT	Returns the price per $100 face value of a security that pays interest at maturity.
PV	Calculates the present value of a loan or an investment, based on a constant interest rate.
RATE	Returns the interest rate per period of an annuity.
RECEIVED	Returns the amount received at maturity for a fully invested security.
RRI	Returns an equivalent interest rate for the growth of an investment.
SLN	Returns the straight-line depreciation of an asset for one period.
SYD	Returns the sum-of-years' digits depreciation of an asset for a specified period.
TBILLEQ	Returns the bond-equivalent yield for a Treasury bill.
TBILLPRICE	Returns the price per $100 face value for a Treasury bill.
TBILLYIELD	Returns the yield for a Treasury bill.
VDB	Returns the depreciation of an asset for any period you specify, including partial periods, using the double-declining balance method or some other method you specify.
XIRR	Returns the internal rate of return for a schedule of cash flows that is not necessarily periodic.
XNPV	Returns the present value for a schedule of cash flows that is not necessarily periodic.
YIELD	Returns the yield on a security that pays periodic interest.
YIELDDISC	Returns the annual yield for a discounted security.
YIELDMAT	Returns the annual yield of a security that pays interest at maturity.
INFO	
INFO.VIEW.COLUMNS	Returns a list of all columns in the current model. Can use in calculations, including calculated tables.
INFO.VIEW.MEASURES	Returns a list of all measures in the current model. Can use in calculations, including calculated tables.
INFO.VIEW.RELATIONSHIPS	Returns a list of all relationships in the current model. Can use in calculations, including calculated tables.
INFO.VIEW.TABLES	Returns a list of all tables in the current model. Can use in calculations, including calculated tables.
INFO.ALTERNATEOFDEFINITIONS	
INFO.ANNOTATIONS	Returns a list of all annotations in the current model with columns matching the schema rowset for annotation objects.
INFO.ATTRIBUTEHIERARCHIES	Represents the TMSCHEMA_ATTRIBUTE_HIERARCHIES DMV query function.
INFO.ATTRIBUTEHIERARCHYSTORAGES	
INFO.CALCDEPENDENCY	Returns information about the calculation dependency for a DAX query.
INFO.CALCULATIONGROUPS	
INFO.CALCULATIONITEMS	
INFO.CATALOGS	Represents the DBSCHEMA_CATALOGS DMV query function.
INFO.CHANGEDPROPERTIES	Represents the TMSCHEMA_CHANGED_PROPERTIES DMV query function.
INFO.COLUMNPARTITIONSTORAGES	
INFO.COLUMNPERMISSIONS	Returns a list of all column permissions in the current model with columns matching the schema rowset for column permissions objects.
INFO.COLUMNS	Returns a list of all columns in the current model with columns matching the schema rowset for column objects.
INFO.COLUMNSTORAGES	Returns a list of all column storages in the current model with columns matching the schema rowset for column storage objects.
INFO.CSDLMETADATA	Returns information about database metadata in XML format.
INFO.CULTURES	Returns a list of all cultures in the current model with columns matching the schema rowset for culture objects.
INFO.DATACOVERAGEDEFINITIONS	
INFO.DATASOURCES	Represents the TMSCHEMA_DATASOURCES DMV query function.
INFO.DELTATABLEMETADATASTORAGES	
INFO.DEPENDENCIES	Returns information about the calculation dependency for a DAX query.
INFO.DETAILROWSDEFINITIONS	Returns a list of all detail rows definitions in the current model with columns matching the schema rowset for detail rows definitions objects.
INFO.DICTIONARYSTORAGES	
INFO.EXCLUDEDARTIFACTS	Represents the TMSCHEMA_EXCLUDED_ARTIFACTS DMV query function.
INFO.EXPRESSIONS	Returns a list of all expressions in the current model with columns matching the schema rowset for expressions objects.
INFO.EXTENDEDPROPERTIES	Returns a list of all extended properties in the current model with columns matching the schema rowset for extended properties objects.
INFO.FORMATSTRINGDEFINITIONS	
INFO.FUNCTIONS	Returns information about the functions that are currently available for use in the DAX programming language. Represents the MDSCHEMA_FUNCTIONS DMV query function, but returns only DAX (and not MDX) functions by default. If the ORIGIN restriction is not specified, it defaults to 3 or 4.
INFO.GENERALSEGMENTMAPSEGMENTMETADATASTORAGES	
INFO.GROUPBYCOLUMNS	
INFO.HIERARCHIES	Represents the TMSCHEMA_HIERARCHIES DMV query function.
INFO.HIERARCHYSTORAGES	
INFO.KPIS	Returns a list of all KPIS in the current model with columns matching the schema rowset for KPI objects.
INFO.LEVELS	Returns a list of all levels in the current model with columns matching the schema rowset for level objects.
INFO.LINGUISTICMETADATA	Represents the TMSCHEMA_LINGUISTIC_METADATA DMV query function.
INFO.MEASURES	Returns a list of all measures in the current model with columns matching the schema rowset for measure objects.
INFO.MODEL	Represents the TMSCHEMA_MODEL DMV query function.
INFO.OBJECTTRANSLATIONS	Returns a list of all object translations in the current model with columns matching the schema rowset for object translation objects.
INFO.PARQUETFILESTORAGES	
INFO.PARTITIONS	Represents the TMSCHEMA_PARTITIONS DMV query function.
INFO.PARTITIONSTORAGES	Returns a list of all partition storages in the current model with columns matching the schema rowset for partition storage objects.
INFO.PERSPECTIVECOLUMNS	Returns a list of all perspective columns in the current model with columns matching the schema rowset for perspective columns objects.
INFO.PERSPECTIVEHIERARCHIES	Returns a list of all perspective hierarchies in the current model with columns matching the schema rowset for perspective hierarchies objects.
INFO.PERSPECTIVEMEASURES	Returns a list of all perspective measures in the current model with columns matching the schema rowset for perspective measures objects.
INFO.PERSPECTIVES	Returns a list of all perspectives in the current model with columns matching the schema rowset for perspectives objects.
INFO.PERSPECTIVETABLES	Returns a list of all perspective tables in the current model with columns matching the schema rowset for perspective tables objects.
INFO.PROPERTIES	Represents the DISCOVER_PROPERTIES DMV query function.
INFO.QUERYGROUPS	
INFO.REFRESHPOLICIES	
INFO.RELATEDCOLUMNDETAILS	
INFO.RELATIONSHIPINDEXSTORAGES	
INFO.RELATIONSHIPS	Represents the TMSCHEMA_RELATIONSHIPS DMV query function.
INFO.RELATIONSHIPSTORAGES	
INFO.ROLEMEMBERSHIPS	Returns a list of all role memberships in the current model with columns matching the schema rowset for role memberships objects.
INFO.ROLES	Returns a list of all roles in the current model with columns matching the schema rowset for roles objects.
INFO.SEGMENTMAPSTORAGES	Returns a list of all segment map storages in the current model with columns matching the schema rowset for segment map storage objects.
INFO.SEGMENTSTORAGES	
INFO.STORAGEFILES	Returns a list of all storage files in the current model with columns matching the schema rowset for storage file objects.
INFO.STORAGEFOLDERS	Returns a list of all storage folders in the current model with columns matching the schema rowset for storage folder objects.
INFO.STORAGETABLECOLUMNS	Returns statistics about the columns of in-memory tables.
INFO.STORAGETABLECOLUMNSEGMENTS	Returns information about the column segments used for storing data for in-memory tables.
INFO.STORAGETABLES	Returns statistics about in-memory tables.
INFO.TABLEPERMISSIONS	Returns a list of all table permissions in the current model with columns matching the schema rowset for table permissions objects.
INFO.TABLES	Returns a list of all tables in the current model with columns matching the schema rowset for table objects.
INFO.TABLESTORAGES	Returns a list of all table storages in the current model with columns matching the schema rowset for table storage objects.
INFO.VARIATIONS	Returns a list of all variations in the current model with columns matching the schema rowset for variations objects.
Information	
COLUMNSTATISTICS	Returns a table of statistics regarding every column in every table in the model.
CONTAINS	Returns true if values for all referred columns exist, or are contained, in those columns; otherwise, the function returns false.
CONTAINSROW	Returns TRUE if a row of values exists or contained in a table, otherwise returns FALSE.
CONTAINSSTRING	Returns TRUE or FALSE indicating whether one string contains another string.
CONTAINSSTRINGEXACT	Returns TRUE or FALSE indicating whether one string contains another string.
CUSTOMDATA	Returns the content of the CustomData property in the connection string.
HASONEFILTER	Returns TRUE when the number of directly filtered values on columnName is one; otherwise returns FALSE.
HASONEVALUE	Returns TRUE when the context for columnName has been filtered down to one distinct value only. Otherwise is FALSE.
ISAFTER	A boolean function that emulates the behavior of a Start At clause and returns true for a row that meets all of the condition parameters.
ISBLANK	Checks whether a value is blank, and returns TRUE or FALSE.
ISBOOLEAN	Checks whether a value is a logical value, (TRUE or FALSE), and returns TRUE or FALSE. Alias of ISLOGICAL.
ISCROSSFILTERED	Returns TRUE when columnName or another column in the same or related table is being filtered.
ISCURRENCY	Checks whether a value is a decimal number, and returns TRUE or FALSE. Alias of ISDECIMAL.
ISDATETIME	Checks whether a value is a date / time, and returns TRUE or FALSE.
ISDECIMAL	Checks whether a value is a decimal number, and returns TRUE or FALSE. Alias of ISCURRENCY.
ISDOUBLE	Checks whether a value is a floating-point number, and returns TRUE or FALSE.
ISEMPTY	Checks if a table is empty.
ISERROR	Checks whether a value is an error, and returns TRUE or FALSE.
ISEVEN	Returns TRUE if number is even, or FALSE if number is odd.
ISFILTERED	Returns TRUE when columnName is being filtered directly.
ISINSCOPE	Returns true when the specified column is the level in a hierarchy of levels.
ISINT64	Checks whether a value is a whole number, and returns TRUE or FALSE. Alias of ISINTEGER.
ISINTEGER	Checks whether a value is a whole number, and returns TRUE or FALSE. Alias of ISINT64.
ISLOGICAL	Checks whether a value is a logical value, (TRUE or FALSE), and returns TRUE or FALSE. Alias of ISBOOLEAN.
ISNONTEXT	Checks if a value is not text (blank cells are not text), and returns TRUE or FALSE.
ISNUMBER	Checks whether a value is a number, and returns TRUE or FALSE. Alias of ISNUMERIC.
ISNUMERIC	Checks whether a value is a number, and returns TRUE or FALSE. Alias of ISNUMBER.
ISODD	Returns TRUE if number is odd, or FALSE if number is even.
ISONORAFTER	A boolean function that emulates the behavior of a Start At clause and returns true for a row that meets all of the condition parameters.
ISSELECTEDMEASURE	Used by expressions for calculation items to determine the measure that is in context is one of those specified in a list of measures.
ISSTRING	Checks if a value is text, and returns TRUE or FALSE. Alias of ISTEXT.
ISSUBTOTAL	Creates another column in a SUMMARIZE expression that returns True if the row contains subtotal values for the column given as argument, otherwise returns False.
ISTEXT	Checks if a value is text, and returns TRUE or FALSE. Alias of ISSTRING.
NONVISUAL	Marks a value filter in a SUMMARIZECOLUMNS expression as non-visual.
SELECTEDMEASURE	Used by expressions for calculation items to reference the measure that is in context.
SELECTEDMEASUREFORMATSTRING	Used by expressions for calculation items to retrieve the format string of the measure that is in context.
SELECTEDMEASURENAME	Used by expressions for calculation items to determine the measure that is in context by name.
USERCULTURE	Returns the locale for the current user.
USERNAME	Returns the domain name and username from the credentials given to the system at connection time.
USEROBJECTID	Returns the current user's Object ID or SID.
USERPRINCIPALNAME	Returns the user principal name.
Logical	
AND	Checks whether both arguments are TRUE, and returns TRUE if both arguments are TRUE.
BITAND	Returns a bitwise 'AND' of two numbers.
BITLSHIFT	Returns a number shifted left by the specified number of bits.
BITOR	Returns a bitwise 'OR' of two numbers.
BITRSHIFT	Returns a number shifted right by the specified number of bits.
BITXOR	Returns a bitwise 'XOR' of two numbers.
COALESCE	Returns the first expression that does not evaluate to BLANK.
FALSE	Returns the logical value FALSE.
IF	Checks a condition, and returns one value when TRUE, otherwise it returns a second value.
IF.EAGER	Checks a condition, and returns one value when TRUE, otherwise it returns a second value. Uses an eager execution plan which always executes the branch expressions regardless of the condition expression.
IFERROR	Evaluates an expression and returns a specified value if the expression returns an error
NOT	Changes FALSE to TRUE, or TRUE to FALSE.
OR	Checks whether one of the arguments is TRUE to return TRUE.
SWITCH	Evaluates an expression against a list of values and returns one of multiple possible result expressions.
TRUE	Returns the logical value TRUE.
