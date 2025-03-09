1. http.[Server](server_test.go) itu struct, bisa diisi property Addr nya dengan localhost dan port 
2. untuk menjalankan test bisa pakai ```go test -v```
3. method ListenAndServe() bagian dari struct http.Server yang mengembalikan error.
4. belajar membuat [handler](handler_test.go) 
5. handler adalah interface, jadi harus diimplementasikan dulu
tapi ada struct implementasi bawaan bernama HandlerFunc type

