function isValidUrl(string) {
  try {
    new URL(string);
    return true;
  } catch (err) {
    return false;
  }
}

console.log(isValidUrl('https://paywithpi.com')); // true
console.log(isValidUrl('invalid-url')); // false
function isValidUrl(string) {
  const regex = /^(https?|ftp):\/\/[^\s/$.?#].[^\s]*$/i;
  return regex.test(string);
}

console.log(isValidUrl('https://paywithpi.com')); // true
console.log(isValidUrl('invalid-url')); // false

const validator = require('validator');

console.log(validator.isURL('https://paywithpi.com')); // true
console.log(validator.isURL('invalid-url')); // false

function isValidHttpUrl(string) {
  try {
    const url = new URL(string);
    return url.protocol === 'http:' || url.protocol === 'https:';
  } catch (err) {
    return false;
  }
}

console.log(isValidHttpUrl('https://paywithpi.com')); // true
console.log(isValidHttpUrl('ftp://paywithpi.com')); // false

