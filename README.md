# sync-acesse-oscar

A server and a daemon to efficiently sync product price data between [Acesse ERP software](https://brasilsoftware.com/site/conheca-acesse) (from [Brasil Software](https://brasilsoftware.com/)) and a system based on the Django Oscar e-commerce library.

Any update to any single price triggers a smart update that can be declined if the existing data is more recent.

Built with Go, PostgreSQL, and SQLC.
