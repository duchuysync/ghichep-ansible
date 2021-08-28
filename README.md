# ghichep-ansible

ansible-playbook test.yml -i host --limit prod

--> những host nào nằm trong group **prod** được khai báo trong trong file **host** sẻ được đẩy qua server remote.

ansible-playbook -i **host** test.yml

--> file config sẻ được đẩy toàn bộ qua tất cả server được khai báo trong **host**
