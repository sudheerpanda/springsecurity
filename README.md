"# springsecurity" 


usefull links:
https://malike.github.io/Spring-Security-OAuth2/



user:
{
    "_id" : "testuser",
    "_class" : "uk.co.caeldev.springsecuritymongo.domain.User",
    "password" : "testpassword",
    "userUUID" : LUUID("03479d48-93cf-5e55-974f-842eb0200ca8"),
    "authorities" : [
        {
            "role" : "ROLE_USER",
            "_class" : "org.springframework.security.core.authority.SimpleGrantedAuthority"
        }
    ],
    "accountNonExpired" : true,
    "accountNonLocked" : true,
    "credentialsNonExpired" : true,
    "enabled" : true
}

MongoClientDetail:
{
    "_id" : "testclient",
    "_class" : "uk.co.caeldev.springsecuritymongo.domain.MongoClientDetails",
    "clientSecret" : "testclientsecret",
    "scope" : [
        "read"
    ],
    "resourceIds" : [
        "oauth2-resource"
    ],
    "authorizedGrantTypes" : [
        "authorization_code",
        "implicit"
    ],
    "registeredRedirectUris" : [
        "http://www.google.co.uk"
    ],
    "authorities" : [
        {
            "role" : "ROLE_CLIENT",
            "_class" : "org.springframework.security.core.authority.SimpleGrantedAuthority"
        }
    ],
    "accessTokenValiditySeconds" : 30000.0000000000000000,
    "refreshTokenValiditySeconds" : 30000.0000000000000000,
    "additionalInformation" : {},
    "autoApproveScopes" : [
        ""
    ]
}