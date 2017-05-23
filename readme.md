PHP Codesniffer Pre-Commit Hook for GIT - Modified for PWT

Based on: 
- https://github.com/s0enke/git-hooks/tree/master/phpcs-pre-commit
- https://gist.github.com/fdemiramon/0423b4308218d417fbf3


REQUIREMENTS

 * Bash
 * PHP CodeSniffer: http://pear.php.net/package/PHP_CodeSniffer/redirected 
   * Check https://docs.joomla.org/Joomla_CodeSniffer for details
   
 
 USAGE

  * Put the script "pre-commit" into your .git/hooks directory or use symbolic links (ln -s ~/path/to/source/perfect-site/hooks/ ~/path/to/target/perfect-site/.git/)
  * OR: add the script to your pre-commit "chain" (you probably know what to do then)
  * Put the Config file "config" into the same dir as the "pre-commit" script and
    edit it to your requirements
  * Ensure that the script is executable. 