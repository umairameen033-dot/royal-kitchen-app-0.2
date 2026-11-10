
# Replace https://YOUR-BACKEND.example.com with the address where server.js runs (no trailing slash).
/api/*  https://YOUR-BACKEND.example.com/api/:splat  200!
/img/*  https://YOUR-BACKEND.example.com/img/:splat  200!
/s/*    https://YOUR-BACKEND.example.com/s/:splat    200!
/admin  /admin.html  200
