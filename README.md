## MAKE W/ MEROXA IN MINUTES, NOT MONTHS

# login 
`meroxa login`

# to delete one connection
`meroxa delete connector origin --yolo`

# Add Postgres Resource . . . 
`meroxa add resource postgresDB --type postgres -u postgres://postgres:postgrespassword/meroxa/port`



# Add mongoDB Resource . . . 
`meroxa add resource mongoDB --type mongodb -u  "mongodb+srv://user:userpassword`


# testing using netcat or telnet
telnet { $POSTGRES_CONNECTION_STRING } /5432

mongo $MONGO_CONNECTION_STRING

# Create Manual Connections 
meroxa create connector smash --from tom --input $TABLE_NAME 