# questionanswer

ข้อที่ 4

```SQL
SELECT * FROM customer WHERE Used > 500000;
```

ข้อที่ 5

```SQL
SELECT 
    c.ID as CustomerID,
    c.Name as CustomerName,
    c.Email,
    c.CountryCode,
    c.Budget,
    c.Used,
    o.ID as OrderID,
    o.Date as OrderDate,
    o.Amount as OrderAmount
FROM customer c
INNER JOIN order_table o ON c.ID = o.CustomerID
ORDER BY c.ID, o.Date;
```

ข้อที่ 6
<img width="1449" height="881" alt="image" src="https://github.com/user-attachments/assets/ebde7fdc-143c-4caa-a1ca-6d58eca367b2" />


ข้อที่ 7
```JavaScript
function WaterCalculate(x) {
    const initialVolume = 5832;
    let currentVolume = initialVolume;

    for (let day = 0; day < x; day++) {
        currentVolume = currentVolume * (2/3);
    }
    
    return currentVolume;
}

function WaterCalculationDetails(days) {
    for (let i = 0; i <= days; i++) {
        const result = WaterCalculate(i);
        const used = i > 0 ? WaterCalculate(i-1) - result : 0;
        
        console.log(`วันที่ ${i}: ใช้ ${used.toFixed(2)} ลิตร, เหลือ ${result.toFixed(2)} ลิตร`);
    }
}

WaterCalculationDetails(7);
```

ข้อที่ 8
```JavaScript
function drawInvertedTriangle(rows) {
    console.log(`Enter number of rows : ${rows}`);
    
    for (let i = 0; i < rows; i++) {
        const spaces = " ".repeat(i);
        const stars = Array(rows - i).fill("*").join(" ");
        console.log(spaces + stars);
    }
}


```

ข้อที่ 9
<img width="464" height="484" alt="image" src="https://github.com/user-attachments/assets/0c93b3f1-a1b5-4b34-8497-b7d90e37f82a" />

 A ∪ B = A + B - A ∩ B

ความน่าจะเป็นที่นักเรียนจะเล่นบาสเก็ตบอลแต่ไม่เล่นฟุตบอล
10/40 = 1/4 = 0.25 = 25%

ข้อที่ 10
ความน่าจะเป็นที่จะหยิบได้ผลไม้ชนิดละ 1 ลูก = 18/120 = 3/20 
0.15 หรือ 15%

ข้อที่ 12
ความน่าจะเป็นที่ผลรวมเป็น 10 = 1/12

ความน่าจะเป็นที่ผลต่างเป็น 2 = 2/9


