# Functions
Types of functions
Funksiya bu- Programming Language da eng ko'p ishlatiladigan katta bir obyekt hisoblanadi.Funksiyalarsiz saytni harakatlantirishning iloji yo'q.Funksiyalar parametr va Argumentlardan iborat bo'ladi. Funksiyalar turiga va xiliga qarab 2 turga bo'linadi."Return&Unreturn" va "Expression funksiya & Decloration funksiyalardir.UnReturn funksiyalar qiymat qaytarmaydigan void bo'lgan funksiyadir.Yangi o'zgaruvchiga olib ishlatib bo'lmaydi.

E.p: function sum(){
  console.log(3+4);
}
let a= sum();
console.log(a); // "Undifined"=unreturn funksiya :)

Return funksiyalar esa aksincha void bo'lmagan ya'ni qiymat qaytaradigan funksiyalar hisoblanadi.
E.p: function sum(a, b){
  return a+b;
}
console.log(sum(3+4)) // "7"=return funksiya :)

Shuningdek, Decloration Function va Expression Functionlarni ko'rib chiqamiz. Ikkalasi deyarli bir ammo asosiy farqi funksiya chaqirilishidadir.

//Decloration Function

E.p: 
sum();
function sum(){
  console.log("Real Madrid")
}
sum();// yani funksiyani tepada ham pastda ham chaqirsa ishlaydi.Faqat yoki pastda yoki tepada bir marta chaqirishni o'zi kifoya.

Aksincha Excpression funcsiya esa 

E.p:
sum(); bu holat ERROR!!!
function sum(){
  console.log("Real Madrid")
}
sum();// FAQAT PASTDA CHAQIRGANDA ISHLAYDI!!!

VA ES6 da yangi funksiya ham kirib kelgan buning nomi Arrow Function dir. JS kodlarini yozayotganda forEach,Map,Filter,Find yana settimeOut SetInterval kabi metodlarni amaliyotda qo'llayotganda kerak bo'ladi.Oddiy funksiya bilan deyarli farqi yo'q ammo yozilishi boshqacharoq. "()=>{}".
E.p: const clubs=[real,barsa,atletiko];
     clubs.forEach((club)=>{
      console.log(club)
     });// real,barsa,atletiko
     
Yuqorida ko'rib chiqqanlarimiz funksiya turlari va xillari edi.funksiyalar mavzusi juda ham katta va uning ichidagi ma'lumotlar ham talaygina.Sizlar uchun tayyorlagan Funksiyalar haqidagi maqolam shu yergacha edi. Etiboringgiz uchun Raxmat!!!    
 
