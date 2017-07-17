# bootstrap-datepicker

This repository is based on [uxsolutions/bootstrap-datepicker](https://github.com/uxsolutions/bootstrap-datepicker). Adding some week related features.

## Added option format keys

* w, ww: Numeric week, no leading zero and leading zero, respectively. Eg, 5, 05.
* e: Numeric day of week, from 1 (Sunday) to 7 (Saturday).
* E, EE: Abbreviated and full day of week names, respectively. Eg, Sat, Saturday.

## Example

Here is a peace of script to show week of this year, and the day number of this week.

```javascript
$('#demo').datepicker({
  format: 'yyyy-w-e'
});
```

The selected date (2017-7-17) will displayed as below:

```
2017-29-2
```

Here is also 'E' and 'EE' examples:

```
2017-29-Mon       // 'yyyy-w-E'
```

```
2017-29-Monday    // 'yyyy-w-EE'
```
