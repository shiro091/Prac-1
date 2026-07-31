#JavaScript学習メモ
//受け取る値の決まり文句
const input = require("fs").readFileSync("/dev/stdin", "utf8").trim();
//2値受け取る場合は以下を追加
const [a, b] = input.split(" ").map(Number);