<template>
  <div class="q-pa-md">
    <pre>
      {{ elektr }}
    </pre>
    <div class="">user_data</div>
    <q-table
      :rows="userData"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Ruyxat</div>
    <q-table
      :rows="ruyxat"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Katm passport</div>
    <q-table
      :rows="katmPassport"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">
      address
      <div class="">AddressRes</div>
      <q-table
        :rows="AddressRes"
        :columns="columns"
        hide-header
        hide-bottom
        :rows-per-page-options="[0]"
      />
      <div class="">AddressReg</div>
      <q-table
        :rows="AddressRes"
        :columns="columns"
        hide-header
        hide-bottom
        :rows-per-page-options="[0]"
      />
      <div class="">Address</div>
      <q-table
        :rows="address"
        :columns="columns"
        hide-header
        hide-bottom
        :rows-per-page-options="[0]"
      />
    </div>
    <div class="">Elektr true</div>
    <q-table
      :rows="elektr1"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr1"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr2"
      :columns="elektr11"
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Elektr folse</div>
    <q-table
      :rows="elektrelse"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr1else"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr2else"
      :columns="elektr11"
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">suv</div>
    <q-table
      :rows="water"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
  </div>
</template>

<script>
const columns = [
  {
    name: "calories",
    align: "left",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "Calories",
    field: "calories",
    sortable: true,
  },
];
const elektr11 = [
  {
    name: "calories",
    align: "left",
    label: "Год",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "месяц",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: "текущий долг",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "непогашенный долг",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "пересмотренный долг",
    field: (row) => row.protein,
  },
  {
    name: "calories",
    align: "left",
    label: "штрафы",
    field: (row) => row.sodium,
  },
];
const userData = [
  {
    name: "first_name",
    calories: "first_name",
  },
  {
    name: "last_name",
    calories: " last_name",
  },
  {
    name: "sur_name",
    calories: "sur_name",
  },
  {
    name: "inn",
    calories: "inn",
  },
  {
    name: "pinfl",
    calories: "pinfl",
  },
  {
    name: "bio_passport_serial",
    calories: "bio_passport_serial",
  },
  {
    name: "bio_passport_number",
    calories: "bio_passport_number",
  },
  {
    name: "bio_passport_issue_date",
    calories: "bio_passport_issue_date",
  },
  {
    name: "bio_passport_expire_date",
    calories: "bio_passport_expire_date",
  },
  {
    name: "bio_passport_whom_given",
    calories: "bio_passport_whom_given",
  },
  {
    name: "birht_date",
    calories: " birht_date",
  },
  {
    name: "address",
    calories: " address",
  },
];
const ruyxat = [
  {
    name: "id",
    calories: "id",
  },
  {
    name: "credit_id",
    calories: "credit_id",
  },
  {
    name: "amount",
    calories: "amount",
  },
  {
    name: "duration",
    calories: "duration",
  },
  {
    name: "name",
    calories: "name",
  },
  {
    name: "passport",
    calories: "passport",
  },
  {
    name: "tin",
    calories: "tin",
  },
  {
    name: "credit_status",
    calories: "credit_status",
  },
  {
    name: "contract_date",
    calories: "contract_date",
  },
  {
    name: "overdue_days",
    calories: "overdue_days",
  },
  {
    name: "merchant_id",
    calories: "merchant_id",
  },
  {
    name: "merchant_name",
    calories: "merchant_name",
  },
];
const katmPassport = [
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "SurnameLatin",
    calories: "SurnameLatin",
  },
  {
    name: "NameLatin",
    calories: "NameLatin",
  },
  {
    name: "MiddleNameLatin",
    calories: "MiddleNameLatin",
  },
  {
    name: "SurnameEng",
    calories: "SurnameEng",
  },
  {
    name: "NameEng",
    calories: "NameEng",
  },
  {
    name: "BirthDate",
    calories: "BirthDate",
  },
  {
    name: "BirthPlaceId",
    calories: "BirthPlaceId",
  },
  {
    name: "BirthCountry",
    calories: "BirthCountry",
  },
  {
    name: "BirthCountryId",
    calories: "BirthCountryId",
  },
  {
    name: "LiveStatus",
    calories: "LiveStatus",
  },
  {
    name: "Nationality",
    calories: "Nationality",
  },
  {
    name: "NationalityId",
    calories: "NationalityId",
  },
  {
    name: "Citizenship",
    calories: "Citizenship",
  },
  {
    name: "CitizenshipId",
    calories: "CitizenshipId",
  },
  {
    name: "Sex",
    calories: "Sex",
  },
  {
    name: "DocGivePlace",
    calories: "DocGivePlace",
  },
  {
    name: "DocGivePlaceId",
    calories: "DocGivePlaceId",
  },
  {
    name: "DateBeginDocument",
    calories: "DateBeginDocument",
  },
  {
    name: "DateEndDocument",
    calories: "DateEndDocument",
  },
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },
];
const AddressRes = [
  {
    name: "Country",
    calories: "Country",
  },
  {
    name: "Region",
    calories: "Region",
  },
  {
    name: "District",
    calories: "District",
  },
  {
    name: "Address",
    calories: "Address",
  },
  {
    name: "RegDate",
    calories: "RegDate",
  },
  {
    name: "Cadastre",
    calories: "Cadastre",
  },
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },
];
const AddressReg = [
  {
    name: "Country",
    calories: "Country",
  },
  {
    name: "Region",
    calories: "Region",
  },
  {
    name: "District",
    calories: "District",
  },
  {
    name: "Address",
    calories: "Address",
  },
  {
    name: "RegDate",
    calories: "RegDate",
  },
  {
    name: "Cadastre",
    calories: "Cadastre",
  },
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },

  {
    Result: "05000",
    ResultMessage: "Successful",
  },
];
const address = [
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },
];
const elektr = [
  {
    name: "state",
    calories: "state",
  },
  {
    name: "message",
    calories: "message",
  },
];
const elektr1 = [
  {
    name: "name",
    calories: "name",
  },
];
const elektr2 = [
  {
    calories: "mar",
    name: "2021",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "apr",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "may",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "jun",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "jul",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
    name: "",
  },
  {
    calories: "aug",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "sep",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "oct",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "nov",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "dec",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
];
const elektr2else = [
  {
    calories: "",
    name: "2021",
    fat: "",
    carbs: "",
    protein: "",
    sodium: "",
  },
];
const elektrelse = [
  {
    name: "state",
    calories: "state",
  },
  {
    name: "message",
    calories: "message",
  },
];
const elektr1else = [
  {
    name: "name",
    calories: "name",
  },
];
const water = [
  {
    name: "ResultCode",
    calories: "ResultCode",
  },
  {
    name: "result_message",
    calories: " result_message",
  },
  {
    name: "abonentfio",
    calories: "abonentfio",
  },
  {
    name: "licshet",
    calories: "licshet",
  },
  {
    name: "passport_number",
    calories: "passport_number",
  },
  {
    name: "pinfl",
    calories: "pinfl",
  },
  {
    name: "kadastrnumber",
    calories: "kadastrnumber",
  },
  {
    name: "phone",
    calories: "phone",
  },
  {
    name: "regions_name",
    calories: "regions_name",
  },
  {
    name: "areas_name",
    calories: "areas_name",
  },
  {
    name: "mahalla_name",
    calories: " mahalla_name",
  },
  {
    name: "streets_name",
    calories: " streets_name",
  },
  {
    name: "address",
    calories: " address",
  },
  {
    name: "company_name",
    calories: " company_name",
  },
  {
    name: "contract_date",
    calories: " contract_date",
  },
  {
    name: "current_liver_count",
    calories: " current_liver_count",
  },
  {
    name: "fmal_saldo",
    calories: " fmal_saldo",
  },
];

export default {
  setup() {
    return {
      columns,
      userData,
      ruyxat,
      katmPassport,
      AddressRes,
      AddressReg,
      address,
      elektr,
      elektr1,
      elektr11,
      elektr2,
      elektrelse,
      elektr1else,
      elektr2else,
      water,
    };
  },
};
</script>
<style lang="scss">
.q-table {
  th {
    border: 0.5px solid black;
  }
  tbody {
    tr {
      td {
        border: 0.5px solid black;
      }
    }
  }
}
</style>
