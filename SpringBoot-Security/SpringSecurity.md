# Spring Security

## Security Session :

    - SecuritySession :
        - Authentication(Only) :
            - UserDetails : CommonLogin
            - OAuth2User : OAuthLogin

    - How to use :
    Authentication <= PrincipalDetails implements UserDetails, OAuthUser

      Why?
      It isn't easy to process both UserDeatils and OAuth2User at the same time in Controller.

## Spring Security

    In OAuth 2.0, there are Authorization code and Client Credential Grant Type
