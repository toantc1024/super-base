# Nhiệm vụ #1: Branch, resolve conflict

#### [toantc1024](https://github.com/toantc1024/)

##### Ở buổi học trước đó, chúng ta đã cùng nhau tìm hiểu về Git là gì và tại sao lại cần Git. Nếu như chưa xem qua bạn có thể xem lại [tại đây](https://github.com/toantc1024/super-base/blob/master/README.md).

## Branch là gì?

Git được chia làm nhiều repo, mỗi repo bạn có thể ví nó như một dự án của bạn. Một dự án có thể chia làm nhiều phiên bản hay nhiều giai đoạn ví dụ như: kiểm thử (test), phát triển (develop), production (hoàn chỉnh), ...

Vậy thì làm sao để chúng ta có thể phân chia thành các phiên bản đó? Đó chính là nhờ có branch trong Git. Branch là việc sao chép các file của nhánh hiện tại (hay phiên bản hiện tại) sang một nhánh khác (phiên bản con).

Ví dụ mình đang có một repo Git như sau:

Bạn có thể khởi tạo một repo Git mới như ở buổi học trước nhé!

![alt text](image-1.png)

là mình đang ở branch master. Bây giờ mình cần phân nhánh để phát triển hàm `sum_of_two_numbers` cho nên mình sẽ tạo một nhánh mới.

Để tạo nhánh mới chúng ta sử dụng lệnh

![alt text](image-2.png)

trong đó <branch_name> là tên nhánh của bạn muốn đặt.

Phiên bản bạn thay đổi trên một nhánh sẽ lưu trên nhánh đó. Để chuyển sang nhánh khác bạn có thể gõ lệnh
`git checkout <branch_name>`

trong đó <switch_branch_name> là tên nhánh bạn muốn chuyển sang (switch_branch_name phải là các nhánh hiện có trên remote/local của repo hiện tại nhe!)

## Branch name đặt gì cũng được ha? 😭 Nooooo

Nếu như bây giờ tớ phân cho đứa bạn code một tính năng nào đó. Ví dụ như một ứng dụng quản lý nhân viên, mình phân cho bạn ấy tính bảng lương của nhân viên thuộc một phòng ban nào đó đi. Bạn ấy đặt tên nhánh là `something`. Bạn sẽ cảm thấy như thế nào nè? P/s: Ultra... thèn quỹ

Cho nên á, chúng ta cần có một quy tắt đặt tên nhánh. Bạn có thể đọc thêm chi tiết tại [bài viết này](https://dev.to/couchcamote/git-branching-name-convention-cch) nhé!

Một số điều chúng ta thường làm là:

Đối với phát triển tính năng feature/<feature_name> VD: feature/salary-table
Đôí với sửa lỗi fix/<bug_name> VD: fix/employee-collision

## Okay, chúng ta đã có nhánh rồi, giờ làm sao để làm việc chung trên nhánh nè?

## Merge

## Conflict resolve in local

## Conflict resolve in Github

## Một số lệnh cập nhật code

### Cảm ơn các bạn đã đọc qua bài viết này nha. 🤟😍
