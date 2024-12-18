---
description: (The different between Population and Sample)
---

# Population and Sample

Trong bài này, ta sẽ tìm hiểu sự khác nhau giữa Population và Sample

## Population

### Khái niệm

Population là một tập data hoàn thiện của một đối tượng object ở 1 lĩnh vực được nhắc đến. Nó chứa tất cả các members của group mà chúng ta thu thập được. Nói cách khác, khi nhắc đến population, ta thường nhắc đến toàn bộ dữ liệu của vấn đề được nói đến.

### Tính chất

1. Data set: chứa toàn bộ data, toàn bộ quan sát
2. Parameter: Parameter là 1 bộ số summarize lại population
   1. E.g: population mean, population variance
3. E.g: Population của tất cả học sinh Việt Nam
   1. Population của tất cả học sinh Việt Nam để hiểu trung bình chiều cao của các học sinh được gọi là population Height mean.
   2. Population: tất cả các customer trong 1 thành phố.

{% hint style="info" %}
Chúng ta không thể nào lấy được tất cả record của 1 sự việc.&#x20;

Hay nói cách khác chúng ta không thể nào hoặc sẽ tốn rất nhiều tài nguyên và chi phí để có được record của toàn bộ member trong tổng thể.&#x20;

Hãy tưởng tượng ta phải đi thu thập toàn bộ income của các dân cư trong 1 thành phố. Điều này nghĩa là ta phải tới từng nhà để hỏi về thu nhập của từng người để đưa ra 1 con số trung bình thu nhập. Điều này gần như không thể.&#x20;


{% endhint %}

> Do đó, ta cần phải chọn 1 thôn, xóm, ở đó gần như chứa gần đủ từng loại người. Từ đó, ta có thể thu thập lương của xóm này. Từ đó ta sẽ có 1 con số trung bình lương, và ta kì vọng nó sẽ gần bằng hoặc xấp xỉ còn số trung bình lương của cả thành phố.
>
> Điều này giúp chúng ta tiết kiệm được chi phí, tài nguyên nhưng được 1 con số gần đúng. Thôn xóm, ở đây gọi là Sample của Thành phố

## Sample

### Khái niệm

Sample là một phần nhỏ của population, đại diện cho 1 phần nào đó (ta kì vọng là gần hết) các tính chất của population

### Tính chất

1. Data set: 1 phần của đối tượng mình nhắm tới
2. Parameter: Sample mean, Sample variance
3. Select the Sample:  Ta biết nó là 1 tập hợp con của population, vậy ta chọn nó như thế nào?
   1. Chọn mẫu xác suất: Đây là phương pháp mà mỗi phần tử đều có một xác suất nhất định và khác không được chọn vào mẫu.

| Tiêu chí                             | Simple Random                                                    | Systematic                                                          | Stratified                                                  | Cluster                                                          |
| ------------------------------------ | ---------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------------------------------- |
| Mục tiêu chính                       | Đảm bảo mỗi phần tử đều có cơ hội được chọn như nhau, tránh bias | Đơn giản, dễ thực hiện, nhanh chóng nhưng vẫn đảm bảo tính đại diện | Thiên về mỗi tầng được đại diện đầy đủ và chính xác         | Tiết kiệm thời gian và chi phí khi mẫu phân tán.                 |
| Cách chia nhóm                       | Không chia nhóm, tổng thể là 1 khối.                             | Không chia nhóm                                                     | Tổng thể được chia thành tầng, dựa trên đặc điểm quan trọng | Tổng thể được chia thành cụm, độc lập tự nhiên                   |
| Cách chọn mẫu                        | Chọn ngẫu nhiên                                                  | Chọn ngẫu nhiên, sau k phần tử lại chọn ngẫu nhiên tiếp             | Chọn ngẫu nhiên từ từng tầng, hoặc theo tỉ lệ.              | Chọn ngẫu nhiên 1 cụm, sau đó chọn toàn cụm hoặc 1 phần của cụm. |
| Tính đồng nhất trong nhchatasKhoong  |                                                                  |                                                                     | Có, đồng nhất về tính chất                                  | Không                                                            |
| Ưu điểm                              |                                                                  |                                                                     |                                                             |                                                                  |
|                                      |                                                                  |                                                                     |                                                             |                                                                  |
|                                      |                                                                  |                                                                     |                                                             |                                                                  |

