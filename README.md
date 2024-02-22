ssl_ciphers "EECDH+AESGCM:EDH+AESGCM:AES256+EECDH:AES256+EDH:HIGH:!aNULL:!MD5:!RC4:!DHE";
ssl_protocols TLSv1 TLSv1.1 TLSv1.2;
ssl_prefer_server_ciphers on;
ssl_session_cache shared:SSL:1m;
ssl_stapling on;
ssl_stapling_verify on;
