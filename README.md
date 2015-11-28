# Reserved words Helper for SMVC

This class contains an array of reserved words for PHP including PHP 7. This can be used to make sure reserved words are not used.

##Install
Add ReservedWords.php to app/Helpers 

##Usage

Create an Alias
````
use Helpers\ReservedWords;
````

Usage Example
````
if(in_array($name, ReservedWords::getList())){
  exit("Name cannot be a reserved word\n");
}
````
