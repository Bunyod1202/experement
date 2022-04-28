<template>
  <div class="q-pa-md">
    <div class="">user_data</div>
    <q-table
      :rows="rows"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Ruyxat</div>
    <q-table
      :rows="rows1"
      :columns="columns1"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Katm passport</div>
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

const rows2 = [
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "Document",
    calories: "Document",
  },
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
