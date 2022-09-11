## Aleksandra Spirina

### **Contacts**
* E-mail: aleksandra.spirina.link@gmail.com
* Telegram: @sunnyname 

### **About myself**
I am a fourth-year student of FAMS BSU, but I still don't know what I will do after graduation. So I'm looking for something new that I can learn. I have basic knowledge in mathematics, algorithms and programming. In addition, I have good soft skills, and I'm still improving them: I dance social dances and conduct yoga classes for my classmates at the university.

### **Skills**
* C++
* Java
* Python (basic)
* HTML5 & CSS (basic)
* Git

### **Code Example**
Solving an algorithmic problem about a frog and mosquitoes on bumps (C++):
```
int64_t frog(std::vector<int64_t> &bumps) {
    int n = bumps.size();
    std::vector<int64_t> results(n);

    results[0] = bumps[0];
    if (n > 1) {
        results[1] = INT64_MIN;
        if (n > 2) {
            results[2] = results[0] + bumps[2];
            for (int i = 3; i < n; ++i) {
                results[i] = std::max(results[i - 2], results[i - 3]) + bumps[i];
            }
        }
    }

    if (results[n - 1] == INT64_MIN) {
        return -1;
    }
    return results[n - 1];
}
```

### **Professional experience**
Programming teacher at the children's IT school since September 2021
### **Education**
* BSU FAMS, 2019 - ... (expected graduation data: 30.06.2023)

### **Languages**
* German - A2 
* English - Elementary (in progress)