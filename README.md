1. const items = ['apple', 'banana', 'apple', 'orange', 'banana', 'apple']; Reduce methodu ilə hər bir meyvənin adının neçə dəfə təkrarlandığını object içərisində göstərin. Mis: {apple: 3, banana: 2, orange: 1}

2. const products = [{ name: 'Laptop', price: 1200, available: true },{ name: 'Phone', price: 800, available: false },{ name: 'Tablet', price: 400, available: true }]; Eyni anda filter, map və reduce metodlarını işlədərək, əvvəlcə available false olanları çıxın, daha sonra qalanların toplam qiymətini göstərin.

3. const numbers = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5]; Verilən array-dən təkrarlanan ədədlərdən sadəcə birini saxlayın. Mis: [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5] ===> [3, 1, 4, 5, 9, 2, 6]

4. const nestedNumbers = [[1, 2, 3], [4, 5, 6], [7, 8]]; Verilən arraydə əvvəlcə array-ləri əsas array-ə çıxardın. Mis: [[1, 2, 3], [4, 5, 6], [7, 8]] ===> [1,2,3,4,5,6,7,8] Daha sonra tək olanları ayrı, cüt olanları ayrı formada toplayıb cavablarını console-da göstərin.

5. const users = [
  { id: 1, username: 'johnDoe', email: 'john@example.com' },
  { id: 2, username: 'janeDoe', email: 'jane@example.com' },
]; Verilən ada görə array içərisində elementi tapacaq funksiya yazın: findByName(users, "johnDoe") ===> { id: 1, username: 'johnDoe', email: 'john@example.com' }

6. const array1 = [1, 3, 5]; const array2 = [2, 4, 6]; Verilmiş 2 array-i birləşdirib daha sonra sıralayın ===> [1,2,3,4,5,6]
