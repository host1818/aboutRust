# aboutRust

When I use rust and diesel to access mysql, I got an error  `could not find native static library 'mysqlclient', perhaps an -L flag is missing?`, It must have `mysqlclient.lib` in you folder `C:\Program Files\MySQL\Connector C++ 8.0\lib64\vs14` and set env `MYSQLCLIENT_LIB_DIR` to the path, I download `mysqlclient.lib` at `https://downloads.mysql.com/archives/c-c/` which version is 6.1.11, It works now.
