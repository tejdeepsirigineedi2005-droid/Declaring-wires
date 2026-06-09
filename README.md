# Declaring-wires

module top_module (
    input a,
    input b,
    input c,
    input d,
    output out,
    output out_n
);

    wire w1, w2, w3;

    assign w1 = a & b;<img width="1366" height="768" alt="Screenshot 2026-06-09 124540" src="https://github.com/user-attachments/assets/08a7c83b-11b8-4ad9-b6d8-35ce51d4e1f5" />
    assign w3 = w1 | w2;

    assign out   = w3;
    assign out_n = ~w3;

endmodule

#output:
#<img width="1366" height="768" alt="Screenshot 2026-06-09 124540" src="https://github.com/user-attachments/assets/48ad1c48-8050-4ee4-bcfc-18ee75a5a9be" />
