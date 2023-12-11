##deploy
sqitch deploy db:pg://postgres:abc123@localhost/flipr_test

##deploy & verify
sqitch deploy --verify db:pg://postgres:abc123@localhost/flipr_test

## verify
sqitch verify db:pg://postgres:abc123@localhost/flipr_test

## status inquery
sqitch status db:pg://postgres:abc123@localhost/flipr_test

## revert
sqitch revert db:pg://postgres:abc123@localhost/flipr_test

## log
sqitch log db:pg://postgres:abc123@localhost/flipr_test


## target
sqitch target add flipr_test db:pg://postgres:abc123@localhost/flipr_test

## target deploy
sqitch engine add pg flipr_test