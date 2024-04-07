# XSS in WonderCMS 3.4.3 (SETTINGS -> SECURITY)
**Software link:** WonderCMS 3.4.3 [https://www.wondercms.com/download]

**@author:** Antonio Díaz.

**Description:** Cross-site scripting (XSS) vulnerability in SECURITY of the SETTINGS section of WonderCMS 3.4.3 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into several fields: 'ADMIN LOGIN URL', 'SITE LANGUAGE CONFIG' and/or 'PAGE DESCRIPTION'.

## PoC
### ADMIN LOGIN URL
1. Enter to SECURITY of the SETTINGS section in the webpage and in 'ADMIN LOGIN URL' set the payload:

![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/f1e9c1df-28fd-4555-8714-22a5a98b07e5)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/2de6b8bf-956c-4b96-b21d-7da4ca7b16fb)
![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/0336e36b-b1b6-46cc-927d-0d25c892e147)

### SITE LANGUAGE CONFIG
1. Enter to SECURITY of the SETTINGS section in the webpage and in any 'SITE LANGUAGE CONFIGURATION' parameter set the payload:

![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/6b97b8d0-b811-4608-8dd9-b5bf125c9ba3)

or

![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/52f8aeef-3f0c-46bc-86eb-152e0356b1fa)



2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/41b1d1a0-3d4b-4576-8469-935aac0096e4)
![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/2e7b526e-0455-47ea-a3d4-6d6f73c3505a)

or

![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/eba47806-2796-4faf-9c70-0add79c68968)
![image](https://github.com/adiapera/xss_security_wondercms_3.4.3/assets/165512291/a26ba390-f1e6-45b1-8fed-2311072afa16)



