//获取所有用户信息
http://localhost:3000/users

//获取ID为1的用户信息
http://localhost:3000/users/1

//获取公司的所有信息
http://localhost:3000/companies

//获取公司的所有信息
http://localhost:3000/companies/1

//获取所有公司ID为3的用户
http://localhost:3000/companies/3/users

//根据公司名字获取信息
http://localhost:3000/companies?name=Microsoft

//根据多个公司名字获取信息
http://localhost:3000/companies?name=Microsoft&name=Apple

//获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2

//升序排序asc  降序desc
http://localhost:3000/companies?_sort=name&_order=asc

//获取年龄30以上
http://localhost:3000/users？age_gte=30

//获取年龄30到40之间
http://localhost:3000/users？age_gte=30&age_lte=40

//搜索用户信息
//获取年龄30以上
http://localhost:3000/users？q=h
