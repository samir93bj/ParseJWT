# ParseJWT
#USE

let token = "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IlNhbWlyIE1haG11ZCIsImlhdCI6MTUxNjIzOTAyMn0.iHkFWw5osAlr-ratwegwK-XA9w9RGkbYzASLyroUePo"

parseJwt(token);

#Result
{
  "sub": "1234567890",
  "name": "Samir Mahmud",
  "iat": 1516239022
}
