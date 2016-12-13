practice JWT in Rails API - follow along from: https://www.sitepoint.com/introduction-to-using-jwt-in-rails/

get JWT:
`curl -X POST -d email="a@a.com" -d password="changeme" http://localhost:3000/auth_user`

get authenticated:
`curl --header "Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyX2lkIjoxfQ.po9twTrX99V7XgAk5mVskkiq8aa0lpYOue62ehubRY4" http://localhost:3000/home`
