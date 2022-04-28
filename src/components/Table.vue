<template>
  <div class="q-pa-md">
    <div class="">1. СУБЪЕКТ КРЕДИТНОЙ ИНФОРМАЦИИ</div>
    <q-table
      :rows="rows"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">2. СКОРИНГ КИАЦ</div>
    <q-table
      :rows="rows1"
      :columns="columns1"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">3. ОБЩИЙ ОБЗОР (ОТКРЫТЫЕ + ЗАКРЫТЫЕ)</div>
    <q-table
      :rows="rows2"
      :columns="columns1"
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

const rows = [
  {
    name: "first_name",
    first_name: "SHERZOD",
  },
  {
    name: "last_name",
    last_name: " SULTANBAYEV",
  },
  {
    name: "sur_name",
    sur_name: "SARVAR O‘G‘LI",
  },
  {
    name: "inn",
    inn: "123456789",
  },
  {
    name: "pinfl",
    pinfl: "33103940270022",
  },
  {
    name: "bio_passport_serial",
    bio_passport_serial: "AA",
  },
  {
    name: "bio_passport_number",
    bio_passport_number: "1637173",
  },
  {
    name: "bio_passport_issue_date",
    bio_passport_issue_date: "2013-05-28 00:00:00",
  },
  {
    name: "bio_passport_expire_date",
    bio_passport_expire_date: "2013-05-28 00:00:00",
  },
  {
    name: "bio_passport_whom_given",
    bio_passport_whom_given: "МИРЗО-УЛУГБЕКСКИЙ РУВД ГОРОДА ТАШКЕНТА",
  },
  {
    name: "birht_date",
    birht_date: " 1994-03-31 00:00:00",
  },
  {
    name: "address",
    address:
      " г. Ташкент, Янгихаётский район, мас. Спутник 22, Дустлик МСГ, 101- Дом, 992- Квартира",
  },
];

const columns1 = [
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

const rows1 = [
  {
    id: 12,
    credit_id: "4656-08",
    amount: 4325345,
    duration: 9,
    name: "Otabek Sabirov",
    passport: "AB1298511",
    tin: "123456789",
    credit_status: "Активный",
    contract_date: "2020-12-01",
    overdue_days: 0,
    merchant_id: 1,
    merchant_name: "Crediton",
  },
];

const rows2 = [
  {
    Document: "AC0356918",
    SurnameLatin: "AGZAMXODJAYEV",
    NameLatin: "BUNYOD",
    MiddleNameLatin: "ZAXITJON O‘G‘LI",
    SurnameEng: "AGZAMKHODJAEV",
    NameEng: "BUNYOD",
    BirthDate: "2002-11-07T00:00:00+05:00",
    BirthPlaceId: "",
    BirthCountry: "УЗБЕКИСТАН",
    BirthCountryId: null,
    LiveStatus: "1",
    Nationality: "УЗБЕК/УЗБЕЧКА",
    NationalityId: 44,
    Citizenship: "УЗБЕКИСТАН",
    CitizenshipId: 182,
    Sex: "1",
    DocGivePlace: "АККУРГАНСКИЙ РОВД ТАШКЕНТСКОЙ ОБЛАСТИ",
    DocGivePlaceId: 27206,
    DateBeginDocument: "2018-11-28T00:00:00+05:00",
    DateEndDocument: "2028-11-27T00:00:00+05:00",
    Result: "05000",
    ResultMessage: "Successful",
  },
];

export default {
  setup() {
    return {
      columns,
      rows,
      rows1,
      rows2,
    };
  },
};
</script>
<style lang="scss">
.q-table {
  tbody {
    tr {
      td {
        width: 50%;
        border: 0.5px solid black;
      }
    }
  }
}
</style>
