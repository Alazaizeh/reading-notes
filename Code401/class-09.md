![api](https://www.okta.com/sites/default/files/styles/1640w_scaled/public/media/image/2020-10/Authentication_vs_Authorization.png?itok=uBFRCfww)
### What header(s) are used in authentication and authorization
The WWW-Authenticate and Proxy-Authenticate response headers
### What is safe to put into a JWT
Do not put secret information in the payload or header elements of a JWT unless it is encrypted.
### How are JWTs validated
Check signature. The last segment of a JWT is the signature, which is used to verify that the token was signed by the sender and not altered in any way.
### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|RBAC| a method of restricting network access based on the roles of individual users within an enterpris|
|User Roles|permission sets that control access to areas and features within the Professional Archive Platform|
|JWT Token|JSON Web Token is a proposed Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key|
