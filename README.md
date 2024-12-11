ДЗ 7. ДЗ 4.3. Робота з switch…case
Переписати код нижче з використанням конструкції switch…case:

const numOrStr = prompt('input number or string');
console.log(numOrStr)

if (numOrStr === null) {
    console.log('ви скасували')
} else if (numOrStr.trim() === '') {
    console.log('Empty String');
} else if (isNaN(+numOrStr)) {
    console.log(' number is Ba_NaN')
} else {
    console.log('OK!')
}
переписаний код має працювати ідентично
