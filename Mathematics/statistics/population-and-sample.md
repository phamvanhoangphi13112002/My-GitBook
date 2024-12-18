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
2. Statistic: Sample mean, Sample variance
3. _**Select the Sample:  Ta biết nó là 1 tập hợp con của population, vậy ta chọn nó như thế nào?**_
   1. Chọn mẫu xác suất: Đây là phương pháp mà mỗi phần tử đều có một xác suất nhất định và khác không được chọn vào mẫu.

<table><thead><tr><th width="132.20001220703125">Tiêu chí</th><th>Simple Random </th><th width="136.199951171875">Systematic </th><th>Stratified</th><th>Cluster</th></tr></thead><tbody><tr><td><strong>Mục tiêu chính</strong></td><td>Đảm bảo mỗi phần tử đều có cơ hội được chọn như nhau, tránh bias</td><td>Đơn giản, dễ thực hiện, nhanh chóng nhưng vẫn đảm bảo tính đại diện</td><td>Thiên về mỗi tầng được đại diện đầy đủ và chính xác</td><td>Tiết kiệm thời gian và chi phí khi mẫu phân tán.</td></tr><tr><td><strong>Cách chia nhóm</strong></td><td>Không chia nhóm, tổng thể là 1 khối.</td><td>Không chia nhóm</td><td>Tổng thể được chia thành tầng, dựa trên đặc điểm quan trọng</td><td>Tổng thể được chia thành cụm, độc lập tự nhiên</td></tr><tr><td><strong>Cách chọn mẫu</strong></td><td>Chọn ngẫu nhiên</td><td>Chọn ngẫu nhiên, sau k phần tử lại chọn ngẫu nhiên tiếp</td><td>Chọn ngẫu nhiên từ từng tầng, hoặc theo tỉ lệ.</td><td>Chọn ngẫu nhiên 1 cụm, sau đó chọn toàn cụm hoặc 1 phần của cụm.</td></tr><tr><td><strong>Tính đồng nhất trong nhóm</strong></td><td>Không yêu cầu</td><td>Không yêu cầu</td><td>Có, đồng nhất về tính chất</td><td>Không</td></tr><tr><td><strong>Ưu điểm</strong></td><td>Đơn giản, không bias và đại diện tốt nếu tổng thể đồng nhất</td><td>Dễ thực hiện, mẫu chọn phân bố đều</td><td>Phù hợp với tổng thể đa dạng, độ chính xác cao</td><td>Phù hợp tổng thể lớn và có sự phân tán địa lí</td></tr><tr><td><strong>Nhược điểm</strong></td><td>Dễ bị bias khi tổng thể đa dạng và phân bố không đều</td><td>Dễ bị bias khi tổng thể mang tính tuần hoàn</td><td>Yêu cầu thông tin có bao nhiêu tầng trước khi chọn mẫu</td><td>Dễ bị bias nếu các cụm không đồng nhất</td></tr><tr><td></td><td></td><td></td><td></td><td></td></tr></tbody></table>

b. Chọn mẫu phi xác suất: là phương pháp không phải các phần tử đều có xác suất được chọn xác định, thường dựa vào phán đoán hoặc tiện cho người nghiên cứu

### Tóm tắt

Mẫu (Sample) là một phần nhỏ của tổng thể (population), được kỳ vọng để đại diện gần hết các tính chất của tổng thể. Có hai phương pháp chính để chọn mẫu:

1. **Chọn mẫu xác suất**: Mỗi phần tử có xác suất nhất định để được chọn. Các phương pháp gồm:
   * _Simple Random_: Đảm bảo công bằng, tránh bias.
   * _Systematic_: Dễ thực hiện, nhanh chóng.
   * _Stratified_: Đảm bảo đại diện đầy đủ các tầng.
   * _Cluster_: Tiết kiệm thời gian và chi phí khi mẫu phân tán.
2. Chọn mẫu phi xác suất: Mỗi phần tử không phải có xác suất được chọn nhất định, thường tùy vào sự phán đoán (domain) và sự tiện lợi của nhà nghiên cứu.

