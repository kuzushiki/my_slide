### 本日の成果発表
@kuzu7shiki

---

### 今日何した？
1. 学会資料作成 (~ 15:00)
2. Rustのお勉強
---

### どこの学会？
IEEE Consumer Communications  
& Networking Conference  
@ラスベガス

---

### 資料チラ見せ
※撮影はNGでお願いします

---

### これからやること
- ひたすら発表練習
- 最低限の日常英会話

---

### Rustってどんな言語？

---

### 強み：「安全性を重視した設計」

---

### Loved部門　第 __1__ 位!! 

##### @Developer Survey Results 2019
---

### とりあえず Hello World!

```
fn main() {
    // 世界よ、こんにちは
    println!("Hello, world!");
}
```
---

### Rustの中心的な機能「所有権」

---

### これは動く？

```
fn main() {
    let x = 5;
    let y = x;
    println!("{}", x);
}
```
- 動きます |

---

### じゃあこれは？

```
fn main() {
    let s1 = String::from("hello");
    let s2 = s1;
    println!("{}", s1);
}
```
- 実は動かない |

- s1はs2に値を渡したので何も持ってない!|
- これが所有権 |

---

### 違いは？

A. 格納先がスタックかヒープか  
こうすることで __二重解放エラー__ が防げる

---

### 質問はありますか？

---


