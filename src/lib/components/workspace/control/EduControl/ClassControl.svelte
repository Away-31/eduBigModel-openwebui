
<main style="background-color: #fefefe;">
  <div class="outbox">
    <div class="form-container">
      <form>
        <div class="input-group" style="padding-bottom: solid">
          课程名称：<input class="bian" style="margin-right: 10px" type="text" name="courseName" placeholder="请输入课程名称">
          班级名称：<input class="bian" style="margin-right: 10px" type="text" name="className" placeholder="请输入班级名称">
          授课老师：<input class="bian" style="margin-right: 10px" type="text" name="teacherName" placeholder="请输入授课老师">
          <button type="submit">查询</button>
          <button type="reset">重置</button>
        </div>
        <div class="button-group" style="display: flex; flex-direction: column; align-items: flex-start; gap: 10px">
          <button class="button-addclass" style="margin: 20px">+ 新增班级</button>
          <script>
            document.querySelector('.button-addclass').addEventListener('click', () => {
              alert("请输入新增加的班级");
            });
          </script>
        </div>
        <div>
          <table style="align-content: flex-start; border: #0d0d0d; " >
            <thead>
              <tr style="height: 20px">
                <th scope="col" style="width: 200px">课程名称</th>
                <th scope="col" style="width: 200px">班级名称</th>
                <th scope="col" style="width: 200px">班级码</th>
                <th scope="col" style="width: 200px">编程语言</th>
                <th scope="col" style="width: 200px">授课教师</th>
                <th scope="col" style="width: 200px">助学情况</th>
                <th scope="col" style="width: 200px">操作</th>
              </tr>
            </thead>
            <tbody>
              <tr style="height: 20px">
                <th scope="row">python课程设计</th>
                <td>codeTest</td>
                <td>22</td>
              </tr>
              <tr style="height: 20px">
                <th scope="row">数据结构</th>
                <td>20233</td>
                <td>45</td>
              </tr>
              <tr style="height: 20px">
                <th scope="row">python设计</th>
                <td>python程序设计</td>
                <td>29</td>
              </tr>
              <tr style="height: 20px">
                <th scope="row">数据结构课程设计</th>
                <td>数据结构课程设…</td>
                <td>36</td>
              </tr>
            </tbody>
          </table>
        </div>
      </form>
    </div>
  </div>
</main>

<script>
  document.addEventListener('DOMContentLoaded', (event) => {
    console.log('==================');
    console.log(event);
  });
</script>

<style>
  .bian {
  border: 1px solid #0d0d0d;
  border-radius: 5px;
  padding: 1px 8px;
  background-color: #f9f9f9;
  color: #333;
  font-size: 15px;
  cursor: pointer;
}

.button-addclass {
  border: 2px solid #0d0d0d;
  border-radius: 12px;
  padding: 5px 20px;
  background-color: #f9f9f9;
  color: #333;
  font-size: 16px;
  cursor: pointer;
}
</style>
