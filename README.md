# jitsi-ad-authentication
Follow this guide: https://github.com/jitsi/jitsi-meet/wiki/LDAP-Authentication#ldap-authentication-for-jitsi-meet-via-ldap2
'''
ldap = {
    hostname = '192.168.1.1',
    bind_dn = 'user1',
    bind_password = '123456',
    use_tls = false,
    user = {
        usernamefield = 'sAMAccountName',
        basedn = 'dc=abc,dc=com',
        filter = '(objectClass=user)',
        -- admin?
        --namefield = 'cn',
    },
}
'''
