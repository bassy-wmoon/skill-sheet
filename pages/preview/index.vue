<template>
  <div>
    <header class="mt-4">
      <div class="d-flex flex-column">
        <div class="text-center">
          <h1>スキルシート</h1>
        </div>
        <div class="text-right">作成日: yyyy年 m月 d日</div>
      </div>
    </header>
    <section class="profile mb-5">
      <div class="profile-basics">
        <div class="d-flex flex-row">
          <div class="w-50">
            <div class="d-flex">
              <span class="d-block w-25 border pl-2 font-weight-bold profile-basics-header">技術者名</span>
              <span class="d-block w-75 border pl-2">A.Z</span>
            </div>
            <div class="d-flex">
              <span class="d-block w-25 border pl-2 font-weight-bold profile-basics-header">年齢</span>
              <span class="d-block w-75 border pl-2">99歳</span>
            </div>
            <div class="d-flex">
              <span class="d-block w-25 border pl-2 font-weight-bold profile-basics-header">学歴</span>
              <span class="d-block w-75 border pl-2">ほげほげ校卒</span>
            </div>
          </div>
          <div class="w-50">
            <div class="d-flex">
              <span class="d-block w-25 border pl-2 font-weight-bold profile-basics-header">所属</span>
              <span class="d-block w-75 border pl-2">ほげほげ株式会社</span>
            </div>
            <div class="d-flex">
              <span class="d-block w-25 border pl-2 font-weight-bold profile-basics-header">性別</span>
              <span class="d-block w-75 border pl-2">男</span>
            </div>
            <div class="d-flex">
              <span class="d-block w-25 border pl-2 font-weight-bold profile-basics-header">最寄り駅</span>
              <span class="d-block w-75 border pl-2">ほげほげ線 ふがふが駅</span>
            </div>
          </div>
        </div>
        <div class="w-100" style="height: 8rem;">
          <div class="d-flex">
            <span class="d-block border pl-2 font-weight-bold profile-basics-header" style="width: 12.5%;">自己PR</span>
            <span class="d-block border pl-2" style="width: 87.5%;">ほげほげ<br>ほげほげ<br>ほげほげ<br>ほげほげ<br>ほげほげ<br>ほげほげ</span>
          </div>
        </div>
      </div>
    </section>

    <section class="mb-5 work-history">
      <table class="border w-100">
        <colgroup>
          <col style="width: 3%" />
          <col style="width: 8%" />
          <col style="width: 39%" />
          <col style="width: 5%" />
          <col style="width: 5%" />
          <col style="width: 5%" />
          <col style="width: 5%" />
          <col style="width: 7%" />
          <col span="7" style="width: 3%" />
        </colgroup>
        <thead class="work-history-header">
          <tr>
            <th scope="col" class="border text-center align-middle" rowspan="2">No</th>
            <th scope="col" class="border text-center align-middle" rowspan="2">期間</th>
            <th scope="col" class="border text-center align-middle" rowspan="2">業務内容</th>
            <th scope="col" class="border text-center align-middle" rowspan="2">規模</th>
            <th scope="col" class="border text-center align-middle" rowspan="2">言語</th>
            <th scope="col" class="border text-center align-middle" rowspan="2">DB</th>
            <th scope="col" class="border text-center align-middle" rowspan="2">サーバ<br>OS</th>
            <th scope="col" class="border text-center align-middle" rowspan="2">FW/MW<br>ツール</th>
            <th scope="col" class="border px-1 py-2 align-middle text-center" colspan="7">担当工程</th>
          </tr>
          <tr>
            <th class="border px-1 py-2 align-top">
              <ul class="mx-auto phase-header">
                <li class="text-center">要</li>
                <li class="text-center">件</li>
                <li class="text-center">定</li>
                <li class="text-center">義</li>
              </ul>
            </th>
            <th class="border px-1 py-2 align-top">
              <ul class="mx-auto phase-header">
                <li class="text-center">基</li>
                <li class="text-center">本</li>
                <li class="text-center">設</li>
                <li class="text-center">計</li>
              </ul>
            </th>
            <th class="border px-1 py-2 align-top">
              <ul class="mx-auto phase-header">
                <li class="text-center">詳</li>
                <li class="text-center">細</li>
                <li class="text-center">設</li>
                <li class="text-center">計</li>
              </ul>
            </th>
            <th class="border px-1 py-2 align-top">
              <ul class="mx-auto phase-header">
                <li class="text-center">実</li>
                <li class="text-center">装</li>
                <li class="text-center">・</li>
                <li class="text-center">単</li>
                <li class="text-center">体</li>
                <li class="text-center">テ</li>
                <li class="text-center">ス</li>
                <li class="text-center">ト</li>
              </ul>
            </th>
            <th class="border px-1 py-2 align-top">
              <ul class="mx-auto phase-header">
                <li class="text-center">結</li>
                <li class="text-center">合</li>
                <li class="text-center">テ</li>
                <li class="text-center">ス</li>
                <li class="text-center">ト</li>
              </ul>
            </th>
            <th class="border px-1 py-2 align-top">
              <ul class="mx-auto phase-header">
                <li class="text-center">総</li>
                <li class="text-center">合</li>
                <li class="text-center">テ</li>
                <li class="text-center">ス</li>
                <li class="text-center">ト</li>
              </ul>
            </th>
            <th class="border px-1 py-2 align-top">
              <ul class="mx-auto phase-header">
                <li class="text-center">保</li>
                <li class="text-center">守</li>
                <li class="text-center">・</li>
                <li class="text-center">運</li>
                <li class="text-center">用</li>
              </ul>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr class="work-history-item">
            <td class="border text-center align-middle px-1">
              1
            </td>
            <td class="border text-left align-middle px-1">
              <ul class="period">
                <li class="text-center">2018年10月</li>
                <li class="text-center">~</li>
                <li class="text-center">2020年9月</li>
              </ul>
              <div class="text-center">
                24ヶ月
              </div>
            </td>
            <td class="border text-left align-middle px-1">
              <p>
                ≪担当業務≫<br />
                ほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふが<br />
                ほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふが
              </p>
              <p>
                ≪習得スキル≫<br />
                ほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふが<br />
                ほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふがほげふが
              </p>
            </td>
            <td class="border text-left align-middle px-1">
              <ul class="scale-list">
                <li class="text-center">全体 99名</li>
                <li class="text-center">開発 99名</li>
                <li class="text-center">チーム 99名</li>
              </ul>
            </td>
            <td class="border text-left align-middle px-1">
              <ul class="language-list">
                <li class="text-center">PHP</li>
                <li class="text-center">Javascript</li>
                <li class="text-center">HTML5</li>
                <li class="text-center">CSS3</li>
                <li class="text-center">SQL</li>
              </ul>
            </td>
            <td class="border text-left align-middle px-1">
              <ul class="db-list">
                <li class="text-center">MySQL</li>
              </ul>
            </td>
            <td class="border text-left align-middle px-1">
              <ul class="server-os-list">
                <li class="text-center">Linux</li>
              </ul>
            </td>
            <td class="border text-left align-middle px-1">
              <ul class="fw-mw-tool-list">
                <li class="text-center">Laravel</li>
                <li class="text-center">Nuxt.js</li>
                <li class="text-center">Vue.js</li>
                <li class="text-center">BootstrapVue</li>
                <li class="text-center">terasoluna-server-framework</li>
              </ul>
            </td>
            <td class="border text-center align-middle">●</td>
            <td class="border text-center align-middle">●</td>
            <td class="border text-center align-middle">●</td>
            <td class="border text-center align-middle">●</td>
            <td class="border text-center align-middle">●</td>
            <td class="border text-center align-middle">●</td>
            <td class="border text-center align-middle">●</td>
          </tr>
        </tbody>
      </table>
    </section>
  </div>
</template>

<script>
export default {
  layout: 'preview',
}
</script>

<style scoped>

</style>
