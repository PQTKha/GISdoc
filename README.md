---
cover: .gitbook/assets/About_citics_header_bg.jpg
coverY: 0
---

# 🇻🇳 Tài liệu xử lý dữ liệu Địa chính & Quy hoạch Việt Nam

:tada:Chào mừng bạn đến với GIS team Citics và đây là toàn bộ tài liệu hướng dẫn cho các quy trình xử lý dữ liệu địa chính và quy hoạch tại GIS team.&#x20;

{% hint style="info" %}
**Lưu ý:** Tài liệu này chỉ được sử dụng lưu hành nội bộ! Không chia sẻ ra bên ngoài dưới mọi hình thức. Các quy trình đang trong quá trình xây dựng và phát triển nên có thể thay đổi dựa vào mức độ phát triển của công cụ cũng như các yêu đầu định hướng phát triển mới. Ngoài ra, các nội dung sẽ được đội ngũ GIS Team cập nhật liên tục trong suốt quá trình làm việc, vì vậy các bạn theo dõi để áp dụng cho xử lý dữ liệu nhằm đảm bảo tính chính xác và đồng bộ!
{% endhint %}

## GIỚI THIỆU

Bộ tài liệu này được biên soạn dựa trên các giai đoạn xử lý dữ liệu địa chính và quy hoạch từ cơ bản đến nâng cao. Các nội dung chính của tài liệu được trình bày theo bố cục như sau:

> Đối với dữ liệu địa chính, dữ liệu đầu vào chính là các tờ bản đồ địa chính được thu thập từ các địa phương trên cả nước Việt Nam. Đây cũng chính là nguồn dữ liệu chính thống và quan trọng nhất trong cơ sở dữ liệu địa chính tại Việt Nam. Chính vì thế, trước khi xử lý dữ liệu thì các chuyên viên phân tích dữ liệu GIS phải thực sự hiểu được các khái niệm cũng như giá trị mà dữ liệu này mang lại, và đây cũng chính là phần nội dung đầu tiên của tài liệu này - **"Phần I: Hiểu các khái niệm và làm quen với dữ liệu địa chính"**. Sở dĩ các bạn phải đọc qua và nghiền ngẫm phần này là vì các bạn chuyên viên phân tích dữ liệu GIS không nhất thiết phải học từ các chuyên ngành như Quản lý Đất Đai, Trắc Địa ...là những ngành được đào tạo chính quy và có liên quan trực tiếp đến các khái niệm cơ bản cũng như nâng cao trong lĩnh vực địa chính. Phần lớn các chuyên viên sẽ đến từ các ngành học khác nhau, ví dụ như Bản đồ, Viễn thám, GIS, Quản lý Tài nguyên Môi trường...Vì vậy để hiểu rõ công việc cũng như các tác vụ trong quy trình xử lý dữ liệu các bạn cần phải hiểu và nắm rõ được các khái niệm cơ bản trong địa chính. Các nguồn tham khảo chính thống và cũng là đầy đủ nhất chính là các văn bản pháp luật (Luật, Thông tư, Quy định,...) trong lĩnh vực địa chính được ban hành từ các Cơ quan như Bộ TNMT, Tổng cục Địa chính hay Cục đo đạc Bản đồ...
>
> Tiếp theo, sau khi tìm hiểu các khác niệm trong lĩnh vực Địa chính, các bạn sẽ đi vào **"Phần II: Chuẩn hóa dữ liệu"**. Vậy tại sao dữ liệu cần phải chuẩn hóa? Và chuẩn hóa dữ liệu như thế nào? Kết quả chuẩn hóa ra sao? hãy cùng tìm hiểu trong phần này.&#x20;
>
> Kết quả thu được từ phần II chính là dữ liệu đầu vào cho quy trình xử lý dữ liệu Semi. Vậy dữ liệu semi là dữ liệu gì? bao gồm những trường thông tin gì? và xử lý như thế nào? Hãy cùng đến với **"Phần III: Xử lý dữ liệu semi"**.&#x20;
>
> Có thể nói rằng với nhiều đơn vị sự nghiệp hay công ty khác, dữ liệu đầu ra từ Phần III đã là "quá đủ" cho việc số hóa dữ liệu địa chính và đã đảm bảo cho việc tra cứu thông tin thửa đất. Tuy nhiên, với CITICS và định hướng phát triển của _**CEO Trần Minh Long**_ thì dữ liệu địa chính không nên dừng lại ở việc mô tả hoặc tra cứu thông tin thửa đất, mà cần phải thực hiện những phân tích chuyên sâu hơn nữa để nhằm cung cấp nhiều thông tin giá trị cho người dùng. Chính vì thế, ngay từ đầu, CEO đã đặt ra nhiều nhiệm vụ cho bộ phận GIS Team, trong đó có nhiệm vụ xử lý và phân tích dữ liệu nâng cao (full) cho dữ liệu địa chính, và đây cũng chính là nội dung của **"Phần IV: Xử lý dữ liệu full"**.&#x20;
>
> Ngoài nhiệm vụ phải đảm bảo dữ liệu địa chính tại CITICS phải bao phủ tất cả 63 tỉnh thành Việt Nam thì phải luôn đảm bảo dữ liệu là chính xác, đầy đủ và cập nhật mới nhất. Để đảm bảo cho độ chính xác của dữ liệu ở từng bước phân tích thì tác vụ QA/QC dữ liệu cũng là một nhiệm vụ hết sức quan trọng của GIS team để đảm bảo rằng tốc độ xử lý dữ liệu nhanh nhưng vẫn phải đảm bảo độ chính xác cao nhất. Và đây cũng là nội dung của **"Phần V: QA/QC dữ liệu và những điêu cần lưu ý"**.&#x20;

{% hint style="info" %}
**Lưu ý:** Quy trình này được biên soạn dựa vào các tác vụ cụ thể được xây dựng và áp dụng tại GIS team. Đồng thời các công cụ được sử dụng trong toàn bộ quy trình xử lý dữ liệu đều đã được bảo mật nhiều lớp để đảm bảo tôn trọng sở hữu trí tuệ và quyền tác giả.&#x20;
{% endhint %}

### NỘI DUNG CHI TIẾT

Các nội dung chính trong chuẩn hóa dữ liệu:

{% tabs %}
{% tab title="DỮ LIỆU ĐỊA CHÍNH" %}
{% content-ref url="du-lieu-dia-chinh/phan-i-chuan-hoa-du-lieu/" %}
[phan-i-chuan-hoa-du-lieu](du-lieu-dia-chinh/phan-i-chuan-hoa-du-lieu/)
{% endcontent-ref %}

{% content-ref url="du-lieu-dia-chinh/phan-ii-xu-ly-du-lieu-semi/" %}
[phan-ii-xu-ly-du-lieu-semi](du-lieu-dia-chinh/phan-ii-xu-ly-du-lieu-semi/)
{% endcontent-ref %}

{% content-ref url="du-lieu-dia-chinh/phan-iii-xu-ly-du-lieu-full/" %}
[phan-iii-xu-ly-du-lieu-full](du-lieu-dia-chinh/phan-iii-xu-ly-du-lieu-full/)
{% endcontent-ref %}
{% endtab %}

{% tab title="DỮ LIỆU QUY HOẠCH" %}

{% endtab %}

{% tab title="DỰ ÁN BẤT ĐỘNG SẢN" %}

{% endtab %}
{% endtabs %}

{% hint style="success" %}
**Kiến thức:** Tài liệu này sẽ cung cấp các kiến thức từ cơ bản đến nâng cao nhằm giúp các bạn chuyên viên bổ sung và củng cố kiến thức trong suốt quá trình xử lý và phân tích dữ liệu.&#x20;
{% endhint %}
