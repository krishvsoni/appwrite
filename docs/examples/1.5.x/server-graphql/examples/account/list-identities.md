query {
    accountListIdentities(
        queries: []
    ) {
        total
        identities {
            _id
            _createdAt
            _updatedAt
            userId
            provider
            providerUid
            providerEmail
            providerAccessToken
            providerAccessTokenExpiry
            providerRefreshToken
        }
    }
}
