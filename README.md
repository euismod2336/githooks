 Githooks
 
 * pre-commit: phpcs/phpcbf the staged files
 
 USAGE

  * Put the script "pre-commit" into your .git/hooks directory or use symbolic links (ln -s ~/path/to/source/perfect-site/hooks/ ~/path/to/target/perfect-site/.git/)
  * OR: add the script to your pre-commit "chain" (you probably know what to do then)
  * Put the Config file "config" into the same dir as the "pre-commit" script and
    edit it to your requirements
  * Ensure that the script is executable. 