# OOS_UTIL_VALIDATION

- [IS_NUMBER Function](#is_number)
- [IS_DATE Function](#is_date)








 
## IS_NUMBER Function<a name="is_number"></a>


<p>
<p>Checks if string is numeric</p>
</p>

### Syntax
```plsql
function is_number(p_str in varchar2)
  return boolean
```

### Parameters
Name | Description
--- | ---
`p_str` | String to validate
*return* | True of p_str is number
 
 





 
## IS_DATE Function<a name="is_date"></a>


<p>
<p>Checks if string is a valid date</p>
</p>

### Syntax
```plsql
function is_date(
  p_str in varchar2,
  p_date_format in varchar2)
  return boolean
```

### Parameters
Name | Description
--- | ---
`p_str` | 
`p_date_format` | 
*return* | True if date is valid
 
 





 