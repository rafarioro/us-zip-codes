An indexed array of zip codes. 

Sample usage

const { usZips } = require('us-zip-codes')

let myZip = usZips[4102]
// returns ==> {"zip_code":4102,"latitude":43.74275,"longitude":-70.44338,"city":"Portland","state":"ME","county":"Cumberland"}

let myZip = usZips[92350]
// returns ==> {"zip_code":92350,"latitude":34.839964,"longitude":-115.967051,"city":"Loma Linda","state":"CA","county":"San Bernardino"}

let myZip = usZips[0]
// returns ==> {"zip_code":0,"data":null}
