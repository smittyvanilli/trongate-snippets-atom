# Smitty's Snippets for the Trongate framework - Atom Editor

## Read Me

### All developers

These snippets are to make life easier and faster then before using the Trongate framework. For sure, this will create a better experience and workflow.


The Trongate website is at [Trongate website](https://trongate.io).

The Trongate framework can be downloaded on Github at [Trongate framework](https://github.com/davidjconnelly/trongate-framework)


### Speed Coding Academy

As a founding member at Speed Coding Academy,
with Trongate, companion tools, and these snippets, there is no doubt you can create anything at lightning fast feeds!

Of course, recommendations are always appreciated inside the forum, if you would like some improvements. Folks at the academy, these are your passports to having lightning speed in the sky.

When you use these snippets with Sublime Text within HTML Files, or HTML within PHP, simply use the less than sign(<). As soon you start typing, it will display all the snippets. If it is directly within PHP itself, it should automatically show all of the Trongate Snippets as soon as you type.


## Other news

### All developers

Once the time is ripe, there are upcoming lessons, so stay tuned for that!

And for a more comprehensive view of the HTML snippets and ones I'm transferring to this Github account:

[Smitty's Trongate Snippets in HTML](https://www.stevenmilley.com/sca/tg-snippets/atom/readme.html)

#### VS Code Extension

And thankfully, there is now a VSCode extension thanks to Simon and Jake:

[Jake and Simon's VSCode Extension](https://marketplace.visualstudio.com/items?itemName=jc-sf.trongate)

## Trongate Snippets

### Table of Trongate snippets

| Snippet Name | Shortcut | Syntax | Characters saved |
| ------------- | ------------- | ------------- | ------------- |
| Trongate Add Floating Cents Function (Two Variables Passed) | tgafc + &lt;Tab&gt; + your amount in dollars | `number_format($your_amount, 2);` | 15 |
| Trongate Anchor Function | tga + &lt;Tab&gt; + your link | ` anchor('your_link')`; | 7 |
| Trongate Class | tgc + &lt;Tab&gt; + Enter Your Classname + &lt;Tab&gt; + Enter your Class statements | class MyClass extends Trongate {<br>&nbsp;&nbsp;&nbsp;Your code goes here.<br>} | 25 |
| Trongate Config Array Assignment | tgcaa + &lt;Tab&gt; + your first variable name + &lt;Tab&gt; + your second variable name | `config[$your_variable1] = $your_variable2;` | 8 |
| Trongate Data Array Assignment | tgda + &lt;Tab&gt; + your array name + &lt;Tab&gt; + your function name | `$your_arrayName = 'your_function_name';` | 2 |  
| Trongate Echo Current Url Function | tgecu + &lt;Tab&gt; Press &lt;Tab&gt; to move the cursor after the semicolon | `echo current_url(your url);` | 14 |  
| Trongate Echo Form Input Function | tgefi + &lt;Tab&gt; + form name + <Ctrl + Enter> | `echo form_input('$form_name');` | 15 |  
| Trongate Echo Form Label Function  | tgefl + &lt;Tab&gt; + your label + <Ctrl + Enter> | `echo form_input('form_label');` | 14 |  
| Trongate Echo Form Submit Function | tgefs + &lt;Tab&gt; + <Ctrl + Enter> | `echo form_submit('submit', 'Submit');` | 31 |
| Trongate Form Textarea Function | tgeft + &lt;Tab&gt; + your text | `echo form_textarea('your_text');` | 17 |
| Trongate Form Close Function | tgfc + &lt;Tab&gt; | `form_close();`  | 8 |
| Trongate Form File Select Function (Two Variables Passed) | tgffs + &lt;Tab&gt; + form name + &lt;Tab&gt; + form attributes | `form_file_select('form_name', 'form_attributes');` | 18 |
| Trongate Form File Select Function (Three Variables Passed) | tgffs3 + &lt;Tab&gt; + form name + &lt;Tab&gt; + form attributes + &lt;Tab&gt; + form additional code | `form_file_select('form_name', 'form_attributes', 'form_additional_code');` | 18 |
| Trongate Form Open Upload Function | tgfou + &lt;Tab&gt; + your form's location + &lt;Tab&gt; + the attributes + &lt;Tab&gt; + any additional code | `form_open_upload($form_location, $attributes, $additional_code);` | 20 |
| Trongate Get Nice Date Class | tggnd + &lt;Tab&gt; | class TimeDate {<br> &nbsp;&nbsp;&nbsp;function get_nice_date($timestamp, $format) {<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;switch ($format) {<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'full':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//FULL<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//Friday 18th of February 2011 at 10:00:00 AM<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('l jS \of F Y \a\t h:i:s A', $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'cool':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//FULL<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// Friday 18th of February 2011<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('l jS \of F Y', $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'shorter':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//SHORTER<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 18th of February 2011<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('jS \of F Y', $time_stamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'american':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//AMERICAN<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// February 18th 2011<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('F jS Y', $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'mini':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//MINI<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 18th Feb 2011<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('jS M Y'), $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'oldschool':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//OLDSCHOOL<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 18/2/11<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = ('j\/n\/y', $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'datepicker':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//DATEPICKER<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 18/2/11<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('d\/m\/Y'), $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break; case 'datepicker_us':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//DATEPICKER_US<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 2/18/11<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('m\/d\/Y', $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'dateandtimepicker':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//DATEANDTIMEPICKER<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 27th July 2018 - 03:50 pm<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('d F Y - H:i a', $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;case 'monyear':<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//MONYEAR<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 18th Feb 2011<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$the_date = date('F Y', $timestamp);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;break;<br>&nbsp;&nbsp;&nbsp;}<br><br>&nbsp;&nbsp;&nbsp;return $the_date;<br>}<br><br>function _is_datepicker_valid($datepicker) {<br>&nbsp;&nbsp;&nbsp;$datepicker_less_slashes = str_replace('/' '', $datepicker);<br>&nbsp;&nbsp;&nbsp;$len = strlen($datepicker_less_slashes);<br>&nbsp;&nbsp;&nbsp;if ((!is_numeric($datepicker_less_slashes)) or ($len !== 8)) {<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return FALSE;<br>&nbsp;&nbsp;&nbsp;} else {<br>&nbsp;&nbsp;&nbsp;return TRUE;<br>&nbsp;&nbsp;&nbsp;}<br>}<br><br>function get_nice_date_from_datepicker($datepicker, $format) {<br>&nbsp;&nbsp;&nbsp;$is_valid = $this->_is_datepicker_valid($datepicker);<br>&nbsp;&nbsp;&nbsp;if ($is_valid == TRUE) {<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$timestamp = $this->make_timestamp_from_datepicker($datepicker);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$nice_date = $this->get_nice_date($timestamp, $format);<br>&nbsp;&nbsp;&nbsp;} else {<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$nice_date = '-';<br>&nbsp;&nbsp;&nbsp;}<br>&nbsp;&nbsp;&nbsp;return $nice_date;<br>}<br><br>function make_timestamp_from_datepicker($datepicker) {<br>&nbsp;&nbsp;&nbsp;$hour = 7;<br>&nbsp;&nbsp;&nbsp;$minute = 0;<br>&nbsp;&nbsp;&nbsp;$second = 0;<br>&nbsp;&nbsp;&nbsp;$day = substr($datepicker, 0, 2);<br>&nbsp;&nbsp;&nbsp;$month = substr($datepicker, 3, 2);<br>&nbsp;&nbsp;&nbsp;$year = substr($datepicker, 6, 4);<br>&nbsp;&nbsp;&nbsp;$timestamp = mktime($hour, $minute, $month, $day, $year);<br>&nbsp;&nbsp;&nbsp;return $timestamp;<br>}<br><br> function make_timestamp_from_dateandtimepicker($dateandtimepicker) {<br>&nbsp;&nbsp;&nbsp;$dateandtimepicker = str_replace('-', '', $dateandtimepicker);<br>&nbsp;&nbsp;&nbsp;$timestamp = strtotime($dateandtimepicker);<br>&nbsp;&nbsp;&nbsp;return $timestamp;<br>}&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><br>function make_timestamp_from_datepicker_us($datepicker) {<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$hour = 7;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$minute = 0;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$second = 0;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$month = substr($datepicker, 0 ,2);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$day = substr($datepicker, 3, 2);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$year = substr($datepicker, 6, 4);><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$timestamp = mktime($hour, $minute, $second, $month, $day, $year);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return $timestamp;<br>}<br><br>function make_timestamp($day, $month, $year) {<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$hour = 7;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$minute = 0;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$second = 0;<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$timestamp = mktime($hour, $minute, $second, $month, $day, $year);<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return $timestamp;<br>&nbsp;&nbsp;&nbsp;}<br>}; | 2897 |
| Trongate HTML BASE_URL | tghbu + &lt;Tab&gt; + Press &lt;Tab&gt; to move the cursor after the closing PHP tag | `<?= BASE_URL ?>` | 9 |
| Trongate HTML Flash Data | tghfd + &lt;Tab&gt; | `<?= flashdata() ?> ` | 12 |
| Trongate HTML Validation Errors | tghve + &lt;Tab&gt; | `<?= validation_errors(); ?>` | 21 |
| Trongate HTML Variable | tghv + &lt;Tab&gt; + Press &lt;Tab&gt; to move the cursor after the closing PHP tag | `<?= $your_variable ?>` | 3 |
| Trongate Logic Expression | tgle + &lt;Tab&gt; + enter your value + Press &lt;Tab&gt; + enter your expression | `your_variable = your_expression;` | -1 |
| Trongate Logic If Else | tglie + &lt;Tab&gt; + enter your IF condition + Press &lt;Tab&gt; + enter the code inside the condition + Press &lt;Tab&gt; + enter the code for the else condition | `if (condition) {<br>&nbsp;&nbsp;&nbsp;if-statements<br>} else {<br>&nbsp;&nbsp;&nbsp;else-statements<br>}  | 26 |
| Trongate Logic If ElseIf | tglei + &lt;Tab&gt; + enter your IF condition + Press &lt;Tab&gt; + enter your code inside the condition + Press &lt;Tab&gt; + enter your ELSEIF condition + Press &lt;Tab&gt; + enter the code for the ELSEIF condition + Press &lt;Tab&gt; + enter your code for the ELSE condition  | if (condition) {<br>&nbsp;&nbsp;&nbsp;if-statements;<br>} elseif (elseif-condition) {<br>&nbsp;&nbsp;&nbsp;elseif-statements;} else {<br>&nbsp;&nbsp;&nbsp;else-statements;<br>} | 19 |
| Trongate Method (No Variables Passed) | tgm + &lt;Tab&gt; + name your function + &lt;Tab&gt; to move the cursor to the method statements | function your_function() {<br>&nbsp;&nbsp;&nbsp;Your method code goes here.<br>}  | 11 |
| Trongate Method (One Variable Passed) | tgm1 + &lt;Tab&gt; + name your function + &lt;Tab&gt; + name of your variable to pass + &lt;Tab&gt; to move cursor to method statements | function your_function(your_variable) {<br>&nbsp;&nbsp;&nbsp;Your method code goes here.<br>} | 7 |
| Trongate Method (Two Variables Passed) | tgm2 + &lt;Tab&gt; + name your function + &lt;Tab&gt; + name of your first variable to pass + &lt;Tab&gt; + name of your second variable to pass &lt;Tab&gt; to move cursor to method statements  | function your_function(your_variable1, your_variable2) {<br>&nbsp;&nbsp;&nbsp;Your method code goes here.<br>} | 8 |
| Trongate Method (Three Variables Passed) | tgm3 + &lt;Tab&gt; + name your function + &lt;Tab&gt; + name of your first variable to pass + &lt;Tab&gt; + name of your second variable to pass &lt;Tab&gt; + name of your third variable to pass + &lt;Tab&gt; to move cursor to method statements  | function your_function(your_variable1, your_variable2, your_variable3) {<br>&nbsp;&nbsp;&nbsp;Your method code goes here.<br>} | 11 |
| Trongate Model Delete Function | tgmd + &lt;Tab&gt; + number / id in table to delete + &lt;Tab&gt; + table name for deletion | ` $this->model->delete(id, 'tableName');` | 19 |
| Trongate Model Get Function (Two Variables Passed) | tgmg + &lt;Tab&gt; + enter which way you want the model ordered by + &lt;Tab&gt; + your target table | `$this->model->get('order_by', 'target_tbl');` | 16 |
| Trongate Model Get Function (Three Variables Passed) | tgmg3 + &lt;Tab&gt; + enter which way you want the model ordered by + &lt;Tab&gt; + your target table &lt;Tab&gt; + your limit | `$this->model->get('order_by', 'target_tbl', 'limit');` | 22 |
| Trongate Model Get Function (Four Variables Passed) | tgmg4 + &lt;Tab&gt; + enter which way you want the model ordered by + &lt;Tab&gt; + your target table &lt;Tab&gt; + your limit + &lt;Tab&gt; + your offset |  | `$this->model->get('order_by', 'target_tbl', 'limit', 'offset');` | 26 |
