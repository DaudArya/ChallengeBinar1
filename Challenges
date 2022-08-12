import kotlin.system.exitProcess
//OOP INHERITENCE
open class bintang{
    open fun cetak(){
        println()
    }
}
open class spiramid : bintang(){
    override fun cetak() {
        super.cetak()
    }
    fun setPiramida() {
        val rows = 8
        for (i in 1..rows) {
            for (j in 1..i) {
                print("* ") }
            cetak() }
    }
}
//OOP INHERITENCE
open class fpiramid:bintang(){
    override fun cetak() {
        super.cetak()
    }
    fun fullPyramid() {
        val rows = 8
        var k = 0
        for (i in 1..rows) {
            for (space in 1..rows - i) {
                print("  ") }
            while (k != 2 * i - 1) {
                print("* ")
                ++k }
            cetak()//implementasi
            k = 0 } }
}

//OOP INHERITENCE
open class revpiramid : bintang(){
    override fun cetak() {
        super.cetak()
    }
    fun RevsFullPyramid() {
        val rows = 8
        for (i in rows downTo 1) {
            for (space in 1..rows - i) {
                print("  ")
            }
            for (j in i..2 * i - 1) {
                print("* ")
            }
            for (j in 0..i - 1 - 1) {
                print("* ")
            }
            cetak()//implementasi
        } }
}


fun belahketupat() {
    val rows = 8
    var k = 0
    for (i in 1..rows) {
        for (space in 1..rows - i) {
            print("  ") }
        while (k != 2 * i - 1) {
            print("* ")
            ++k }
        println()
        k = 0 }
    val baris = 8
    for (i in baris downTo 1) {
        for (space in 1..baris - i+1) {
            print("  ") }
        for (j in i..2 * i - 3) {
            print("* ") }
        for (j in 0..i - 1 - 1) {
            print("* ") }
        println() } }

//OOP POLYMORPHISM
class simbol{
    fun x() {
        val rows = 9
        for (i in 1..rows) {
            for (j in 1..rows) {
                if (i==j || i+j == rows + 1){
                    print("*")
                } else {
                    print(" ") } }
            println() } }

    fun plus(){
        val rows = 9
        for (i in 1..rows) {
            for (j in 1..rows) {
                if (i==(rows/2)+1 || j == (rows/2)+1){
                    print(" *")
                } else {
                    print("  ") } }
            println() }
    }
}
fun x() {
    val rows = 9
    for (i in 1..rows) {
        for (j in 1..rows) {
            if (i==j || i+j == rows + 1){
                print("*")
            } else {
                print(" ") } }
        println() } }

fun plus(){
    val rows = 9
    for (i in 1..rows) {
        for (j in 1..rows) {
            if (i==(rows/2)+1 || j == (rows/2)+1){
                print(" *")
            } else {
                print("  ") } }
        println() }
}

fun main(args: Array<String>){
    do{
        println()
    println("Program Membuat Pola")
    println("Silahkan Pilih Pola yang akan dibuat")
    println("1.Piramid")
    println("2.Piramid Terbalik")
    println("3.Belah Ketupat")
    println("4.Huruf X")
    println("5.Setengah Segitiga")
    println("6.Plus Bintang")
    println("7.Keluar")

    print("Silahkan Pilih Pola Nomor : ")

    var angka : Int

        angka = readLine()!!.toInt()

        when(angka){
            1 -> fpiramid().fullPyramid()
            2 -> revpiramid().RevsFullPyramid()
            3 -> belahketupat()
            4 -> simbol().x()
            5 -> spiramid().setPiramida()
            6 -> simbol().plus()
            7 -> exitProcess(0)
        }

    }while (angka<=7)

}


