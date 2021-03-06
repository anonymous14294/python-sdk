# LoginRadius Python SDK Change Log

# Version 3.2.0
## Enhancements
  - Updated demo with new UI and features.
  - Unit tests.
  - Bug fixes.
  - New V2 API's:     
      - Auth Privacy Policy Accept   
      - Auth Send Welcome Email   
      - Auth Verify Email by OTP    
      - Auth Delete Account    
      - Account Email Delete    
      - Phone Login Using OTP   
      - Phone Send OTP   
      - Remove Phone ID by Access Token   
      - 2FA Validate Google Auth Code   
      - 2FA Validate OTP   
      - Validate Backup Code   
      - Update MFA by Access Token   
      - Update MFA Setting   
      - One Touch Verify OTP by Email   
      - Get Active Session Details   
      - Access Token via Vkontakte Token   
      - Access Token via Google Token   
      - Refresh User Profile   
      - Refresh Token   
      - Delete All Records by Datasource   

###Breaking Changes
  - Replaced deprecated [pycrypto package](https://pypi.org/project/pycrypto/) with [cryptography package](https://pypi.org/project/cryptography/) for SOTT generation
  - Updated some existing API's:    
      - Get Roles by UID: moved to role class    
      - Assign Roles by UID: moved role class    
      - One Touch Login: moved to authentication.login class   
      - Get Backup Code by Access Token: moved to authentication.TwoFactor class   
      - Reset Backup Code by Access Token: moved to authentication.TwoFactor class   
      - Get Backup Code by UID: moved to account.TwoFactor class   
      - Reset Backup Code by UID: moved to account.TwoFactor class

# Version 3.1.1
## Bug Fixed
  - Fixed HTTP method request bug.

# Version 3.1.0
## Enhancements
  - Passed API key and Secret key in herader for management API's.
  - Passed SOTT In header.
  - Added Management API to generate a SOTT.
  - Implemented ability to support proxy server.
  - Supported NULL and projection in fields.
  - Added new V2 API's.

# Version 3.0
## Enhancements
  - Added Latest V2 APIs.