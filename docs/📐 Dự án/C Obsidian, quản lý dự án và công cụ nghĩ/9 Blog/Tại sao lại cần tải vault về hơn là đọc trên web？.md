---
share: true
created: 2023-05-26T14:51
updated: 2023-10-28T11:50
---
Trong ngành khoa học máy tính, [Việc hợp tác làm việc thời gian thực với dữ liệu được lưu ở local là một bài toán khó](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/H%E1%BB%A3p%20t%C3%A1c%20l%C3%A0m%20vi%E1%BB%87c/Vi%E1%BB%87c%20h%E1%BB%A3p%20t%C3%A1c%20l%C3%A0m%20vi%E1%BB%87c%20th%E1%BB%9Di%20gian%20th%E1%BB%B1c%20v%E1%BB%9Bi%20d%E1%BB%AF%20li%E1%BB%87u%20%C4%91%C6%B0%E1%BB%A3c%20l%C6%B0u%20%E1%BB%9F%20local%20l%C3%A0%20m%E1%BB%99t%20b%C3%A0i%20to%C3%A1n%20kh%C3%B3.md). Điều đó khiến cho [chúng ta phải đánh đổi giữa sự tự do sử dụng dữ liệu và sự tiện lợi trong việc hợp tác](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/%C4%90%C3%A1nh%20%C4%91%E1%BB%95i/C%C3%B3%20s%E1%BB%B1%20%C4%91%C3%A1nh%20%C4%91%E1%BB%95i%20gi%E1%BB%AFa%20s%E1%BB%B1%20t%E1%BB%B1%20do%20s%E1%BB%AD%20d%E1%BB%A5ng%20d%E1%BB%AF%20li%E1%BB%87u%20v%C3%A0%20s%E1%BB%B1%20ti%E1%BB%87n%20l%E1%BB%A3i%20trong%20vi%E1%BB%87c%20h%E1%BB%A3p%20t%C3%A1c.md). Hay nói cách khác, [Việc trung tâm hoá việc lưu trữ dữ liệu trên máy chủ sẽ lấy đi autonomy và agency của người dùng cuối](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/H%E1%BB%A3p%20t%C3%A1c%20l%C3%A0m%20vi%E1%BB%87c/Vi%E1%BB%87c%20trung%20t%C3%A2m%20ho%C3%A1%20vi%E1%BB%87c%20l%C6%B0u%20tr%E1%BB%AF%20d%E1%BB%AF%20li%E1%BB%87u%20tr%C3%AAn%20m%C3%A1y%20ch%E1%BB%A7%20s%E1%BA%BD%20l%E1%BA%A5y%20%C4%91i%20autonomy%20v%C3%A0%20agency%20c%E1%BB%A7a%20ng%C6%B0%E1%BB%9Di%20d%C3%B9ng%20cu%E1%BB%91i.md). Xu thế hiện nay là [Các nhóm làm việc qua mạng ngày càng nhiều](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/H%E1%BB%A3p%20t%C3%A1c%20l%C3%A0m%20vi%E1%BB%87c/C%C3%A1c%20nh%C3%B3m%20l%C3%A0m%20vi%E1%BB%87c%20qua%20m%E1%BA%A1ng%20ng%C3%A0y%20c%C3%A0ng%20nhi%E1%BB%81u.md), đến nỗi khi được hỏi về app đa số mọi người sẽ chỉ nhắc đến những cloud app như Google Drive hay Notion. Nghĩa là chúng ta đã hy sinh quá nhiều sự tự chủ dữ liệu cho sự tiện lợi đến nỗi chúng ta không còn biết gì về một loạt các phần mềm khác mạnh mẽ hơn. Việc đánh mất sự tự chủ đó là lý do khiến cho chúng ta luôn cảm thấy mình mù công nghệ, và chấp nhận rằng mình sẽ chẳng hiểu gì về công nghệ cả. Đây chính là một sự bất lực học được. [Người không học về lập trình thấy việc lập trình như làm phép thuật](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/L%E1%BA%ADp%20tr%C3%ACnh/Ng%C6%B0%E1%BB%9Di%20kh%C3%B4ng%20h%E1%BB%8Dc%20v%E1%BB%81%20l%E1%BA%ADp%20tr%C3%ACnh%20th%E1%BA%A5y%20vi%E1%BB%87c%20l%E1%BA%ADp%20tr%C3%ACnh%20nh%C6%B0%20l%C3%A0m%20ph%C3%A9p%20thu%E1%BA%ADt.md), trong khi [Lập trình viên biết lập trình chủ yếu là nhờ biết google](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/L%E1%BA%ADp%20tr%C3%ACnh/L%E1%BA%ADp%20tr%C3%ACnh%20vi%C3%AAn%20bi%E1%BA%BFt%20l%E1%BA%ADp%20tr%C3%ACnh%20ch%E1%BB%A7%20y%E1%BA%BFu%20l%C3%A0%20nh%E1%BB%9D%20bi%E1%BA%BFt%20google.md). Bạn cũng biết google vậy, vậy tại sao vẫn thấy nó giống như làm phép thuật? Chúng tôi nghĩ một phần lớn là vì đã từ lâu bạn không còn cảm giác mình có sự tự chủ với dữ liệu của mình rồi. Khi bạn đã có lại được cảm giác đó, bạn sẽ thấy mình tự tin hơn về công nghệ.

Bạn có thể bắt đầu có lại cảm giác đó bằng cách tải dữ liệu của web này về.

[Hướng dẫn tải vault](../3%20Th%C3%A0nh%20ph%E1%BA%A9m/Ph%E1%BA%A7n%20m%E1%BB%81m/B%E1%BB%99%20c%C3%A0i/H%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn%20t%E1%BA%A3i%20vault.md){ .md-button .md-button--primary }

# Những thứ mà chỉ phiên bản trên Obsidian mới có mà bản web không có
Về cơ bản, những thứ này có được là do [Obsidian lưu dữ liệu nằm trên máy của người dùng](../../../%E2%9A%94%EF%B8%8F%20H%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn%20Obsidian%20v%C3%A0%20Git/%F0%9F%92%8E%20Gi%E1%BB%9Bi%20thi%E1%BB%87u%20v%E1%BB%81%20Obsidian/M%C3%B4%20t%E1%BA%A3%20v%E1%BB%81%20Obsidian/Obsidian%20l%C6%B0u%20d%E1%BB%AF%20li%E1%BB%87u%20n%E1%BA%B1m%20tr%C3%AAn%20m%C3%A1y%20c%E1%BB%A7a%20ng%C6%B0%E1%BB%9Di%20d%C3%B9ng.md). Đây là một số hệ quả của việc đó:

## Tất cả các phím tắt, chức năng và plugin của Obsidian, bao gồm cả những thứ bạn thiết lập riêng cho mình
Ví dụ:
### Đồ thị mối liên hệ giữa các ghi chú trong phần [⚡Hiểu biết sâu](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/index.md)
![](https://i.imgur.com/gwdeLlL.png)

Đồ thị này cho thấy được có những ghi chú nào nổi trội trong đây, cũng như mức độ liên kết của chúng. Bạn có thể thấy chúng rời rạc khá nhiều.

### Những trang nào liên kết tới trang đang đọc
![](https://i.imgur.com/UbXZspz.png)

### Lịch sử phát triển 
![](https://i.imgur.com/UyIxTHF.png)
Xem thêm:: [Obsidian có những tính năng nào hay?](../../../%E2%9A%94%EF%B8%8F%20H%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn%20Obsidian%20v%C3%A0%20Git/%F0%9F%92%8E%20Gi%E1%BB%9Bi%20thi%E1%BB%87u%20v%E1%BB%81%20Obsidian/Theo%20t%C3%ADnh%20n%C4%83ng%20c%E1%BB%A7a%20plugin/index.md)

## Thời gian chuyển trang gần như là tức thời
Điều này giúp bạn nhanh chóng kiểm tra giả thiết các câu hỏi của bạn.

## Các file không thể hoặc không cần phải để lên web
Ví dụ:
- Các file PDF hoặc thu âm do không phải là định dạng markdown nên sẽ không có YAML. Mà plugin tạo web, [Mkdocs Publisher](https://obsidian-publisher.netlify.app/github%20publisher/commands/#upload "Commands - Obsidian Mkdocs Publisher") đòi hỏi phải có từ khoá `share` trong YAML thì mới đăng lên web
- Các file trong thư mục `Thiết lập` dù ở dạng markdown nhưng việc để lên web cũng không cần thiết
- Các file có dung lượng lớn hơn 100 MB thì GitHub không chịu nhận

# Vậy bản web được sinh ra để làm gì?
- Dễ giới thiệu cho người mới, 
- Dễ quảng bá dự án,
- ~~Tăng SEO~~  Thêm nguồn tài nguyên chất lượng cho các máy tìm kiếm như Google, Bing
- Thêm nguồn ngữ liệu chất lượng để huấn luyện cho máy

## Những lỗi trên bản web 
- Search 
- Nếu có h1 ngay đầu ghi chú thì tiêu đề sẽ là cái h1 đó
- Không tự chuyển trang nên hay gặp 404
- Cache 🤡

Ví dụ, những trang có dataview sẽ không chắc được cập nhật, do plugin tạo web không thấy trang đó có sự thay đổi gì.

Về cơ bản, **những lỗi này không được ưu tiên sửa**. Do nhiệm vụ của nó là để dễ giới thiệu cho người mới, nên khi nó đã làm xong nhiệm vụ của mình thì có lẽ nên tập trung sức lực cho những thứ khác. Để biết những thứ cần được ưu tiên hơn, bạn có thể đọc trong [📐 Dự án](../../index.md).

[Hướng dẫn tải vault](../3%20Th%C3%A0nh%20ph%E1%BA%A9m/Ph%E1%BA%A7n%20m%E1%BB%81m/B%E1%BB%99%20c%C3%A0i/H%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn%20t%E1%BA%A3i%20vault.md){ .md-button .md-button--primary }
