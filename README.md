// myanmarUnicodeData.js - Myanmar Unicode Standard Complete Mapping (U+1000 - U+104F)

const MYANMAR_UNICODE_DATA = {
  // 1. ဗျည်းများ (Consonants - U+1000 to U+1021)
  consonants: [
    { char: "က", code: "U+1000", hex: "\u1000", name: "KA" },
    { char: "ခ", code: "U+1001", hex: "\u1001", name: "KHA" },
    { char: "ဂ", code: "U+1002", hex: "\u1002", name: "GA" },
    { char: "ဃ", code: "U+1003", hex: "\u1003", name: "GHA" },
    { char: "င", code: "U+1004", hex: "\u1004", name: "NGA" },
    { char: "စ", code: "U+1005", hex: "\u1005", name: "CA" },
    { char: "ဆ", code: "U+1006", hex: "\u1006", name: "CHA" },
    { char: "ဇ", code: "U+1007", hex: "\u1007", name: "JA" },
    { char: "ဈ", code: "U+1008", hex: "\u1008", name: "JHA" },
    { char: "ဉ", code: "U+1009", hex: "\u1009", name: "NYA" },
    { char: "ည", code: "U+100A", hex: "\u100A", name: "NNYA" },
    { char: "ဋ", code: "U+100B", hex: "\u100B", name: "TTA" },
    { char: "ဌ", code: "U+100C", hex: "\u100C", name: "TTHA" },
    { char: "ဍ", code: "U+100D", hex: "\u100D", name: "DDA" },
    { char: "ဎ", code: "U+100E", hex: "\u100E", name: "DDHA" },
    { char: "ဏ", code: "U+100F", hex: "\u100F", name: "NNA" },
    { char: "တ", code: "U+1010", hex: "\u1010", name: "TA" },
    { char: "ထ", code: "U+1011", hex: "\u1011", name: "THA" },
    { char: "ဒ", code: "U+1012", hex: "\u1012", name: "DA" },
    { char: "ဓ", code: "U+1013", hex: "\u1013", name: "DHA" },
    { char: "န", code: "U+1014", hex: "\u1014", name: "NA" },
    { char: "ပ", code: "U+1015", hex: "\u1015", name: "PA" },
    { char: "ဖ", code: "U+1016", hex: "\u1016", name: "PHA" },
    { char: "ဗ", code: "U+1017", hex: "\u1017", name: "BA" },
    { char: "ဘ", code: "U+1018", hex: "\u1018", name: "BHA" },
    { char: "မ", code: "U+1019", hex: "\u1019", name: "MA" },
    { char: "ယ", code: "U+101A", hex: "\u101A", name: "YA" },
    { char: "ရ", code: "U+101B", hex: "\u101B", name: "RA" },
    { char: "လ", code: "U+101C", hex: "\u101C", name: "LA" },
    { char: "ဝ", code: "U+101D", hex: "\u101D", name: "WA" },
    { char: "သ", code: "U+101E", hex: "\u101E", name: "SA" },
    { char: "ဟ", code: "U+101F", hex: "\u101F", name: "HA" },
    { char: "ဠ", code: "U+1020", hex: "\u1020", name: "LLA" },
    { char: "အ", code: "U+1021", hex: "\u1021", name: "A" }
  ],

  // 2. သီးခြားသရများ (Independent Vowels - U+1023 to U+102A)
  independentVowels: [
    { char: "ဣ", code: "U+1023", hex: "\u1023", name: "I" },
    { char: "ဤ", code: "U+1024", hex: "\u1024", name: "II" },
    { char: "ဥ", code: "U+1025", hex: "\u1025", name: "U" },
    { char: "ဦ", code: "U+1026", hex: "\u1026", name: "UU" },
    { char: "ဧ", code: "U+1027", hex: "\u1027", name: "E" },
    { char: "ဩ", code: "U+1029", hex: "\u1029", name: "O" },
    { char: "ဪ", code: "U+102A", hex: "\u102A", name: "AU" }
  ],

  // 3. သရသင်္ကေတများနှင့် အသတ်များ (Dependent Vowels & Diacritics - U+102B to U+103A)
  vowelsAndDiacritics: [
    { char: "ါ", code: "U+102B", hex: "\u102B", name: "TALL AA" },
    { char: "ာ", code: "U+102C", hex: "\u102C", name: "AA" },
    { char: "ိ", code: "U+102D", hex: "\u102D", name: "I" },
    { char: "ီ", code: "U+102E", hex: "\u102E", name: "II" },
    { char: "ု", code: "U+102F", hex: "\u102F", name: "U" },
    { char: "ူ", code: "U+1030", hex: "\u1030", name: "UU" },
    { char: "ေ", code: "U+1031", hex: "\u1031", name: "E" },
    { char: "ဲ", code: "U+1032", hex: "\u1032", name: "AI" },
    { char: "ံ", code: "U+1036", hex: "\u1036", name: "ANUSVARA" },
    { char: "့", code: "U+1037", hex: "\u1037", name: "DOT BELOW" },
    { char: "း", code: "U+1038", hex: "\u1038", name: "VISARGA" },
    { char: "်", code: "U+103A", hex: "\u103A", name: "ASAT" }
  ],

  // 4. ဗျည်းတွဲများနှင့် အောက်ဆင့် (Medials & Virama - U+1039 to U+103F)
  medialsAndVirama: [
    { char: "္", code: "U+1039", hex: "\u1039", name: "VIRAMA (Subscript Stacker)" },
    { char: "ျ", code: "U+103B", hex: "\u103B", name: "MEDIAL YA" },
    { char: "ြ", code: "U+103C", hex: "\u103C", name: "MEDIAL RA" },
    { char: "ွ", code: "U+103D", hex: "\u103D", name: "MEDIAL WA" },
    { char: "ှ", code: "U+103E", hex: "\u103E", name: "MEDIAL HA" },
    { char: "ဿ", code: "U+103F", hex: "\u103F", name: "GREAT SA" }
  ],

  // 5. ဂဏန်းများ (Digits - U+1040 to U+1049)
  digits: [
    { char: "၀", code: "U+1040", hex: "\u1040", name: "ZERO" },
    { char: "၁", code: "U+1041", hex: "\u1041", name: "ONE" },
    { char: "၂", code: "U+1042", hex: "\u1042", name: "TWO" },
    { char: "၃", code: "U+1043", hex: "\u1043", name: "THREE" },
    { char: "၄", code: "U+1044", hex: "\u1044", name: "FOUR" },
    { char: "၅", code: "U+1045", hex: "\u1045", name: "FIVE" },
    { char: "၆", code: "U+1046", hex: "\u1046", name: "SIX" },
    { char: "၇", code: "U+1047", hex: "\u1047", name: "SEVEN" },
    { char: "၈", code: "U+1048", hex: "\u1048", name: "EIGHT" },
    { char: "၉", code: "U+1049", hex: "\u1049", name: "NINE" }
  ],

  // 6. ပုဒ်ဖြတ် ပုဒ်ရပ်များနှင့် သင်္ကေတများ (Punctuation & Symbols - U+104A to U+104F)
  punctuationAndSymbols: [
    { char: "၊", code: "U+104A", hex: "\u104A", name: "LITTLE SECTION (Comma)" },
    { char: "။", code: "U+104B", hex: "\u104B", name: "SECTION (Period)" },
    { char: "၌", code: "U+104C", hex: "\u104C", name: "LOCATIVE" },
    { char: "၎င်း", code: "U+104D", hex: "\u104D", name: "COMPLETED" },
    { char: "၍", code: "U+104E", hex: "\u104E", name: "AFOREMENTIONED" },
    { char: "၏", code: "U+104F", hex: "\u104F", name: "GENITIVE" }
  ]
};

if (typeof module !== "undefined" && module.exports) {
  module.exports = MYANMAR_UNICODE_DATA;
}

