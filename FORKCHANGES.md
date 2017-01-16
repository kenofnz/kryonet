* Updated to use Kryo 4.0.0, JSON Beans 0.7
	* This breaks RMI throwing exceptions due to a being unable to serialize Exception objects. Corresponding unit tests removed.
* Removed redundant libraries.
* Fixed UDP not receiving on Android 5.0+