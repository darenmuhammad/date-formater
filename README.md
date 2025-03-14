# ***Date Formater***

## Table of JavaScript Date Methods

| Method                 | Description |
|------------------------|-------------|
| `new Date()`           | Membuat objek tanggal baru berdasarkan waktu sekarang atau berdasarkan nilai yang diberikan (misalnya string tanggal, timestamp, atau tahun-bulan-tanggal). |
| `.getFullYear()`       | Mengembalikan tahun dari objek `Date`. |
| `.getMonth()`          | Mengembalikan bulan (0-11, di mana Januari adalah 0). |
| `.getDate()`           | Mengembalikan tanggal dalam bulan (1-31). |
| `.getDay()`            | Mengembalikan hari dalam seminggu (0-6, di mana Minggu adalah 0). |
| `.getHours()`          | Mengembalikan jam (0-23). |
| `.getMinutes()`        | Mengembalikan menit (0-59). |
| `.getSeconds()`        | Mengembalikan detik (0-59). |
| `.getMilliseconds()`   | Mengembalikan milidetik (0-999). |
| `.getTime()`           | Mengembalikan timestamp dalam milidetik sejak 1 Januari 1970 (UNIX Epoch). |
| `.setFullYear(year)`   | Mengatur tahun dalam objek `Date`. |
| `.setMonth(month)`     | Mengatur bulan (0-11). |
| `.setDate(day)`        | Mengatur tanggal dalam bulan. |
| `.toISOString()`       | Mengembalikan string dalam format ISO (YYYY-MM-DDTHH:mm:ss.sssZ). |
| `.toLocaleDateString()`| Mengembalikan tanggal dalam format lokal. |
| `.toLocaleTimeString()`| Mengembalikan waktu dalam format lokal. |

## Table of String Methods

| Method                 | Description |
|------------------------|-------------|
| `.split("")`          | Memisahkan setiap karakter dalam string menjadi array elemen individu. |
| `.split(" ")`         | Memisahkan string berdasarkan spasi, menghasilkan array kata-kata dalam kalimat. |
| `.split("-")`         | Memisahkan string berdasarkan tanda `-` dan mengembalikan array elemen. |
| `.reverse()`           | Membalik urutan elemen dalam array. Hanya bisa digunakan pada array, jadi biasanya digunakan setelah `.split()` untuk membalikkan string. |
| `.join("")`           | Menggabungkan elemen array menjadi string tanpa pemisah. |
| `.join(" ")`          | Menggabungkan elemen array menjadi string dengan spasi sebagai pemisah. |
| `.join("-")`          | Menggabungkan elemen array menjadi string dengan tanda `-` sebagai pemisah. |

## Example Usage

### `new Date()`
```javascript
const now = new Date();
console.log(now.toISOString()); // Contoh: "2025-03-11T14:30:00.000Z"
```

### `.split("")`
```javascript
const text = "hello";
console.log(text.split("")); // ["h", "e", "l", "l", "o"]
```

### `.split(" ")`
```javascript
const sentence = "Hello World";
console.log(sentence.split(" ")); // ["Hello", "World"]
```

### `.split("-")`
```javascript
const date = "2025-03-11";
console.log(date.split("-")); // ["2025", "03", "11"]
```

### `.reverse()`
```javascript
const arr = [1, 2, 3, 4, 5];
console.log(arr.reverse()); // [5, 4, 3, 2, 1]
```

### `.join("")`
```javascript
const letters = ["H", "e", "l", "l", "o"];
console.log(letters.join("")); // "Hello"
```

### `.join(" ")`
```javascript
const words = ["Hello", "World"];
console.log(words.join(" ")); // "Hello World"
```

### `.join("-")`
```javascript
const dateArray = ["2025", "03", "11"];
console.log(dateArray.join("-")); // "2025-03-11"
```

