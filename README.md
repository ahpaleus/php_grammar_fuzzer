# php_grammar_fuzzer
PHP grammar fuzzer based on dharma (Mozilla Security)

Example usage:  
```php
✗ dharma -grammar php_grammar.dg
[Dharma] 2020-05-29 14:34:40,253 INFO: Machine random seed: -5517621903007805456
[Dharma] 2020-05-29 14:34:40,254 DEBUG: Using configuration from: /usr/local/lib/python2.7/site-packages/dharma/settings.py
[Dharma] 2020-05-29 14:34:40,255 DEBUG: Processing grammar content of ../../../usr/local/lib/python2.7/site-packages/dharma/grammars/common.dg
[Dharma] 2020-05-29 14:34:40,259 DEBUG: Processing grammar content of php_grammar.dg
try { try {  $vars["DOMText"]->isWhitespaceInElementContent(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { proc_open("-1", array("a" => 0.1111, "b" => "-9223372036854775809", "c" => 9223372036854775807 ), $ref_array, "%00%0a%0d", array("a" => 1.79769313486e+308, "b" => "-1", "c" => 0.1111 ), array("a" => 0xff, "b" => "%00%0a%0d", "c" => 8446744073709551616 )); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionFunction"]->invokeArgs(array("a" => 65536, "b" => "-9223372036854775809", "c" => 0.678426 )); } catch (Exception $e) { } } catch(Error $e) { }
try { try { mb_strstr("-9223372036854775809", "\x00", true, "%00%0a%0d"); } catch (Exception $e) { } } catch(Error $e) { }
try { try { lcg_value(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { random_int(357913942, 0x3fffffff); } catch (Exception $e) { } } catch(Error $e) { }
try { try { array_diff_key(array("a" => 255, "b" => "\xff", "c" => 65535 ), array("a" => 0xfffffffe, "b" => "-9223372036854775809", "c" => -9223372036854775809 ), array("a" => -357913942, "b" => "\x00", "c" => -1.97684995314e+16 )); } catch (Exception $e) { } } catch(Error $e) { }
try { try { $vars["DOMNodeList"]->item(1); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionClassConstant"]->getDocComment(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { curl_setopt_array(fopen("/tmp/doesntexist", "w"), array("a" => 79228162514264337593543950336l, "b" => "%00%0a%0d", "c" => 0x100000 )); } catch (Exception $e) { } } catch(Error $e) { }
try { try { fgetss(fopen("/tmp/doesntexist", "w"), 4294967296, "m"); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionGenerator"]->getExecutingGenerator(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { ctype_alnum("%00%0a%0d"); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["Directory"]->close(fopen("/tmp/doesntexist", "w")); } catch (Exception $e) { } } catch(Error $e) { }
try { try { $vars["DOMNodeList"]->count(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionFunction"]->getClosure(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { min(-2147483648, -65535); } catch (Exception $e) { } } catch(Error $e) { }
try { try { $vars["DOMNode"]->C14N(true, 1, array("a" => -1.97684995314e+16, "b" => "\xff", "c" => 0x10000 ), array("a" => 1.79769313486e+308, "b" => "k", "c" => 0.1111 )); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["SplFileObject"]->key(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { ignore_user_abort(1); } catch (Exception $e) { } } catch(Error $e) { }
try { try { $vars["DateInterval"]->format("\xff"); } catch (Exception $e) { } } catch(Error $e) { }
try { try { gzopen("-1", "v", 0x1000); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["Error"]->getCode(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { connection_aborted(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionType"]->allowsNull(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { popen("\x00", "%00%00%00"); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["MultipleIterator"]->key(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["DOMText"]->isWhitespaceInElementContent(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionGenerator"]->getFunction(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionParameter"]->getClass(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ReflectionParameter"]->isPassedByReference(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { posix_setpgid(0x1000, 32768); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["DOMDocumentFragment"]->appendXML("-9223372036854775809"); } catch (Exception $e) { } } catch(Error $e) { }
try { try { set_time_limit(-0); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["SplFixedArray"]->next(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["SplDoublyLinkedList"]->pop(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { openssl_pkcs12_export(array("a" => 0xff, "b" => "%00%0a%0d", "c" => 0xffffffff ), $ref_string, array("a" => 18446744073709551616, "b" => "%00%0a%0d", "c" => 0xff ), "w", array("a" => -2147483648, "b" => "\xff", "c" => 2.07564741538e+16 )); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["DOMElement"]->setAttributeNS("%00%0a%0d", "%00%00%00", "-1"); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["DOMImplementation"]->createDocument("%00%00%00", "-1",  new DOMDocumentType()); } catch (Exception $e) { } } catch(Error $e) { }
try { try { flock(fopen("/etc/passwd", "r"), 0, $ref_int); } catch (Exception $e) { } } catch(Error $e) { }
try { try { $vars["DateInterval"]->createFromDateString("\xff"); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["ErrorException"]->getSeverity(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { ksort($ref_array, 0xff); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["SessionHandler"]->open("%00%00%00", "\xff"); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["DOMDocument"]->saveXML(new DOMNode(), 0x1000); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["MultipleIterator"]->next(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["DOMText"]->splitText(357913942); } catch (Exception $e) { } } catch(Error $e) { }
try { try { mhash(65536, "-9223372036854775809", "-1"); } catch (Exception $e) { } } catch(Error $e) { }
try { try { xmlwriter_start_dtd_attlist(fopen("/dev/null", "r"), "%00%0a%0d"); } catch (Exception $e) { } } catch(Error $e) { }
try { try { proc_close(fopen("/etc/passwd", "r")); } catch (Exception $e) { } } catch(Error $e) { }
try { try { hash_copy(hash_init("md5")); } catch (Exception $e) { } } catch(Error $e) { }
try { try { get_browser("%00%0a%0d", 0); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["MultipleIterator"]->countIterators(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["Error"]->getMessage(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["SplDoublyLinkedList"]->getIteratorMode(); } catch (Exception $e) { } } catch(Error $e) { }
try { try { putenv("-1"); } catch (Exception $e) { } } catch(Error $e) { }
try { try { dom_import_simplexml(new SimpleXMLElement("<lt>a<gt>a<lt>/a<gt>")); } catch (Exception $e) { } } catch(Error $e) { }
try { try { strspn("\xff", "-1", -0, 32768); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["SplDoublyLinkedList"]->getIteratorMode(); } catch (Exception $e) { } } catch(Error $e) { }
try { try {  $vars["DOMXPath"]->query("\xff", new DOMNode(), false); } catch (Exception $e) { } } catch(Error $e) { }
try { try { flock(fopen("/etc/passwd", "r"), 0xff, $ref_int); } catch (Exception $e) { } } catch(Error $e) { }
try { try { asort($ref_array, 65536); } catch (Exception $e) { } } catch(Error $e) { }
try { try { usort($ref_array, "phpinfo"); } catch (Exception $e) { } } catch(Error $e) { }
```
