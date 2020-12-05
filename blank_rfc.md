# PHP RFC: Your Title Here 
  * Version: 0.9
  * Date: 2013-02-24 (use today's date here)
  * Author: Your Name, your_email_address@example.com
  * Status: Draft (or Under Discussion or Accepted or Declined)
  * First Published at: http://wiki.php.net/rfc/your_rfc_name

This is a suggested template for PHP Request for Comments (RFCs). Change this template to suit your RFC.  Not all RFCs need to be tightly specified.  Not all RFCs need all the sections below.

Read https://wiki.php.net/rfc/howto carefully!

## Introduction 
The elevator pitch for the RFC. The first paragraph of this section will be slightly larger to give it emphasis; please write a good introduction.

## Proposal 
All the features and examples of the proposal.

To [paraphrase Zeev Suraski](http://news.php.net/php.internals/66051), explain hows the proposal brings substantial value to be considered
for inclusion in one of the world's most popular programming languages.

Remember that the RFC contents should be easily reusable in the PHP Documentation.

If applicable, you may wish to use the language specification as a reference.

## Backward Incompatible Changes 
What breaks, and what is the justification for it?

## Proposed PHP Version(s) 
List the proposed PHP versions that the feature will be included in.  Use relative versions such as "next PHP 8.x" or "next PHP 8.x.y".

## RFC Impact 
### To SAPIs 
Describe the impact to CLI, Development web server, embedded PHP etc.

### To Existing Extensions 
Will existing extensions be affected?

### To Opcache 
It is necessary to develop RFC's with opcache in mind, since opcache is a core extension distributed with PHP.

Please explain how you have verified your RFC's compatibility with opcache.

### New Constants 
Describe any new constants so they can be accurately and comprehensively explained in the PHP documentation.

### php.ini Defaults 
If there are any php.ini settings then list:
  * hardcoded default values
  * php.ini-development values
  * php.ini-production values

## Open Issues 
Make sure there are no open issues when the vote starts!

## Unaffected PHP Functionality 
List existing areas/features of PHP that will not be changed by the RFC.

This helps avoid any ambiguity, shows that you have thought deeply about the RFC's impact, and helps reduces mail list noise.

## Future Scope 
This section details areas where the feature might be improved in future, but that are not currently proposed in this RFC.

## Proposed Voting Choices 
Include these so readers know where you are heading and can discuss the proposed voting options.

## Patches and Tests 
Links to any external patches and tests go here.

If there is no patch, make it clear who will create a patch, or whether a volunteer to help with implementation is needed.

Make it clear if the patch is intended to be the final patch, or is just a prototype.

For changes affecting the core language, you should also provide a patch for the language specification.

## Implementation 
After the project is implemented, this section should contain
  - the version(s) it was merged into
  - a link to the git commit(s)
  - a link to the PHP manual entry for the feature
  - a link to the language specification section (if any)

## References 
Links to external references, discussions or RFCs

## Rejected Features 
Keep this updated with features that were discussed on the mail lists.