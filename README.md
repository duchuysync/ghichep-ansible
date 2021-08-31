# ghichep-ansible

ansible-playbook test.yml -i host --limit prod

--> những host nào nằm trong group **prod** được khai báo trong trong file **host** sẻ được đẩy qua server remote.

ansible-playbook -i **host** test.yml

--> file config sẻ được đẩy toàn bộ qua tất cả server được khai báo trong **host**


| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |
