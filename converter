function convertToRoman(num) {
let nums = 
  {
    1:'I',
    4:'IV',
    5:'V',
    9:'IX',
    10:'X',
    40:'XL',
    50:'L',
    90:'XC',
    100:'C',
    400:'CD',
    500:'D',
    900:'CM',
    1000:'M'
  };

  let length = Object.keys(nums).length;
  let keys = Object.keys(nums);
  let out = '';
  console.log(length)
  
  for(let i = length-1; i >= 0; i--){
   // console.log(nums[keys[i]]);
    while(keys[i] <= num) {
      num -= keys[i];
      out += nums[keys[i]];
    }

  }
  console.log(out)

 return out;
}

convertToRoman(36);