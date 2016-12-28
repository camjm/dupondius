# dupondius
A personal accounting web app

## Model

### Currencies
* Symbol
* Code
* Conversion Rate

1-to-many with Markets

### Markets
* Country
* Name

1-to-many with Companies

### Companies
* Name
* Code

1-to-many with Products

### Products
* Code

1-to-many with Holdings

### Holdings
* Date
* Amount

### Users
* Name

1-to-many with Holdings
