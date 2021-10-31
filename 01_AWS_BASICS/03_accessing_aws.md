## Accessing AWS
There are 3 options to access AWS
1. AWS managed console(protected by password +MFA)
2. AWS CLI(protected by access keys)
3. AWS SDK(for code, protected by access keys)

### Access keys
- Access keys can be generated from AWS console.
- Access keys  are like username and password
   Access Key ID ~= username
   Secret Access Key ~= password 
- AWS users can manage their own access keys

### AWS SDK
- AWS software development Kit(AWS SDK)
- Language specific APIs (set of libraries)
- Enables us to manage access and manage AWS services progrmmatically.
- Can be embeded within our application.

### AWS CLI
- Tool to allow access AWS using command line shell.
- Is AWS  SDK for Python called **Boto**.
- Code is opensource
- Allows direct access to the public API's of AWS services
