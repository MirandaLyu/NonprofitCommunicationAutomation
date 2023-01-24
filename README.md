# NonprofitCommunicationAutomation
- Built software on a team of 3 that helps a nonprofit automate communication with their supporters who have signed up to receive emails or letters
- Established a program to receive users’ inputs, read supporters’ information in a CSV file and write emails or letters based on templates using Java.io and Java.nio packages
- Tested via JUnit and reached coverage by 82%

#### The program should accept the following command line arguments in any order: 
- --email        Generate email messages. If this option is provided, then --email-template must also be provided. 
- --email-template <path/to/file>          A filename for the email template. 
- --letter       Generate letters. If this option is provided, then --letter-template must also be provided. 
- --letter-template <path/to/file>         A filename for the letter template.
- --output-dir <path/to/folder>            The folder to store all generated files. This option is required.
- --csv-file <path/to/file>                The CSV file to process. This option is required.
