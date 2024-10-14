# DE01
```Csharp
frmSinhvien.Designer.cs
namespace DE01
{
    partial class frmSinhvien
    {
        /// <summary>
        /// Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        /// Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        /// Required method for Designer support - do not modify
        /// the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            this.label1 = new System.Windows.Forms.Label();
            this.label2 = new System.Windows.Forms.Label();
            this.label3 = new System.Windows.Forms.Label();
            this.txtMSV = new System.Windows.Forms.TextBox();
            this.dtNgaysinh = new System.Windows.Forms.DateTimePicker();
            this.label4 = new System.Windows.Forms.Label();
            this.label5 = new System.Windows.Forms.Label();
            this.txtHoten = new System.Windows.Forms.TextBox();
            this.cmblop = new System.Windows.Forms.ComboBox();
            this.textBox3 = new System.Windows.Forms.TextBox();
            this.button1 = new System.Windows.Forms.Button();
            this.ListView = new System.Windows.Forms.ListView();
            this.btnthem = new System.Windows.Forms.Button();
            this.btnxoa = new System.Windows.Forms.Button();
            this.btnsua = new System.Windows.Forms.Button();
            this.btnluu = new System.Windows.Forms.Button();
            this.btnkluu = new System.Windows.Forms.Button();
            this.btnthoat = new System.Windows.Forms.Button();
            this.SuspendLayout();
            // 
            // label1
            // 
            this.label1.AutoSize = true;
            this.label1.Font = new System.Drawing.Font("Microsoft Sans Serif", 25.8F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.label1.Location = new System.Drawing.Point(63, 24);
            this.label1.Name = "label1";
            this.label1.Size = new System.Drawing.Size(337, 51);
            this.label1.TabIndex = 0;
            this.label1.Text = "Thong tin chi tiet";
            // 
            // label2
            // 
            this.label2.AutoSize = true;
            this.label2.Location = new System.Drawing.Point(175, 95);
            this.label2.Name = "label2";
            this.label2.Size = new System.Drawing.Size(81, 16);
            this.label2.TabIndex = 1;
            this.label2.Text = "Ma sinh vien";
            // 
            // label3
            // 
            this.label3.AutoSize = true;
            this.label3.Location = new System.Drawing.Point(205, 123);
            this.label3.Name = "label3";
            this.label3.Size = new System.Drawing.Size(67, 16);
            this.label3.TabIndex = 2;
            this.label3.Text = "Ngay sinh";
            // 
            // txtMSV
            // 
            this.txtMSV.Location = new System.Drawing.Point(262, 89);
            this.txtMSV.Name = "txtMSV";
            this.txtMSV.Size = new System.Drawing.Size(100, 22);
            this.txtMSV.TabIndex = 3;
            // 
            // dtNgaysinh
            // 
            this.dtNgaysinh.Location = new System.Drawing.Point(278, 117);
            this.dtNgaysinh.Name = "dtNgaysinh";
            this.dtNgaysinh.Size = new System.Drawing.Size(200, 22);
            this.dtNgaysinh.TabIndex = 4;
            // 
            // label4
            // 
            this.label4.AutoSize = true;
            this.label4.Location = new System.Drawing.Point(524, 95);
            this.label4.Name = "label4";
            this.label4.Size = new System.Drawing.Size(46, 16);
            this.label4.TabIndex = 5;
            this.label4.Text = "Ho ten";
            // 
            // label5
            // 
            this.label5.AutoSize = true;
            this.label5.Location = new System.Drawing.Point(524, 122);
            this.label5.Name = "label5";
            this.label5.Size = new System.Drawing.Size(55, 16);
            this.label5.TabIndex = 6;
            this.label5.Text = "Lop hoc";
            // 
            // txtHoten
            // 
            this.txtHoten.Location = new System.Drawing.Point(599, 92);
            this.txtHoten.Name = "txtHoten";
            this.txtHoten.Size = new System.Drawing.Size(145, 22);
            this.txtHoten.TabIndex = 7;
            // 
            // cmblop
            // 
            this.cmblop.FormattingEnabled = true;
            this.cmblop.Location = new System.Drawing.Point(599, 119);
            this.cmblop.Name = "cmblop";
            this.cmblop.Size = new System.Drawing.Size(121, 24);
            this.cmblop.TabIndex = 8;
            // 
            // textBox3
            // 
            this.textBox3.Font = new System.Drawing.Font("Microsoft Sans Serif", 16.2F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.textBox3.Location = new System.Drawing.Point(33, 200);
            this.textBox3.Name = "textBox3";
            this.textBox3.Size = new System.Drawing.Size(162, 38);
            this.textBox3.TabIndex = 10;
            // 
            // button1
            // 
            this.button1.Font = new System.Drawing.Font("Microsoft Sans Serif", 24F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.button1.Location = new System.Drawing.Point(201, 182);
            this.button1.Name = "button1";
            this.button1.Size = new System.Drawing.Size(106, 66);
            this.button1.TabIndex = 11;
            this.button1.Text = "Tìm";
            this.button1.UseVisualStyleBackColor = true;
            // 
            // ListView
            // 
            this.ListView.HideSelection = false;
            this.ListView.Location = new System.Drawing.Point(99, 254);
            this.ListView.Name = "ListView";
            this.ListView.Size = new System.Drawing.Size(793, 306);
            this.ListView.TabIndex = 18;
            this.ListView.UseCompatibleStateImageBehavior = false;
            // 
            // btnthem
            // 
            this.btnthem.Location = new System.Drawing.Point(313, 215);
            this.btnthem.Name = "btnthem";
            this.btnthem.Size = new System.Drawing.Size(75, 23);
            this.btnthem.TabIndex = 19;
            this.btnthem.Text = "Them";
            this.btnthem.UseVisualStyleBackColor = true;
            // 
            // btnxoa
            // 
            this.btnxoa.Location = new System.Drawing.Point(403, 215);
            this.btnxoa.Name = "btnxoa";
            this.btnxoa.Size = new System.Drawing.Size(75, 23);
            this.btnxoa.TabIndex = 20;
            this.btnxoa.Text = "Xoa";
            this.btnxoa.UseVisualStyleBackColor = true;
            // 
            // btnsua
            // 
            this.btnsua.Location = new System.Drawing.Point(499, 215);
            this.btnsua.Name = "btnsua";
            this.btnsua.Size = new System.Drawing.Size(75, 23);
            this.btnsua.TabIndex = 21;
            this.btnsua.Text = "Sua";
            this.btnsua.UseVisualStyleBackColor = true;
            // 
            // btnluu
            // 
            this.btnluu.Location = new System.Drawing.Point(599, 215);
            this.btnluu.Name = "btnluu";
            this.btnluu.Size = new System.Drawing.Size(75, 23);
            this.btnluu.TabIndex = 22;
            this.btnluu.Text = "Luu";
            this.btnluu.UseVisualStyleBackColor = true;
            // 
            // btnkluu
            // 
            this.btnkluu.Location = new System.Drawing.Point(701, 215);
            this.btnkluu.Name = "btnkluu";
            this.btnkluu.Size = new System.Drawing.Size(75, 23);
            this.btnkluu.TabIndex = 23;
            this.btnkluu.Text = "K.Luu";
            this.btnkluu.UseVisualStyleBackColor = true;
            // 
            // btnthoat
            // 
            this.btnthoat.Location = new System.Drawing.Point(798, 215);
            this.btnthoat.Name = "btnthoat";
            this.btnthoat.Size = new System.Drawing.Size(75, 23);
            this.btnthoat.TabIndex = 24;
            this.btnthoat.Text = "Thoat";
            this.btnthoat.UseVisualStyleBackColor = true;
            // 
            // frmSinhvien
            // 
            this.AutoScaleDimensions = new System.Drawing.SizeF(8F, 16F);
            this.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font;
            this.ClientSize = new System.Drawing.Size(988, 593);
            this.Controls.Add(this.btnthoat);
            this.Controls.Add(this.btnkluu);
            this.Controls.Add(this.btnluu);
            this.Controls.Add(this.btnsua);
            this.Controls.Add(this.btnxoa);
            this.Controls.Add(this.btnthem);
            this.Controls.Add(this.button1);
            this.Controls.Add(this.textBox3);
            this.Controls.Add(this.cmblop);
            this.Controls.Add(this.txtHoten);
            this.Controls.Add(this.label5);
            this.Controls.Add(this.label4);
            this.Controls.Add(this.dtNgaysinh);
            this.Controls.Add(this.txtMSV);
            this.Controls.Add(this.label3);
            this.Controls.Add(this.label2);
            this.Controls.Add(this.label1);
            this.Controls.Add(this.ListView);
            this.Name = "frmSinhvien";
            this.Text = "DANH SACH SINH VIEN";
            this.ResumeLayout(false);
            this.PerformLayout();

        }

        #endregion

        private System.Windows.Forms.Label label1;
        private System.Windows.Forms.Label label2;
        private System.Windows.Forms.Label label3;
        private System.Windows.Forms.TextBox txtMSV;
        private System.Windows.Forms.DateTimePicker dtNgaysinh;
        private System.Windows.Forms.Label label4;
        private System.Windows.Forms.Label label5;
        private System.Windows.Forms.TextBox txtHoten;
        private System.Windows.Forms.ComboBox cmblop;
        private System.Windows.Forms.TextBox textBox3;
        private System.Windows.Forms.Button button1;
        private System.Windows.Forms.ListView ListView;
        private System.Windows.Forms.Button btnthem;
        private System.Windows.Forms.Button btnxoa;
        private System.Windows.Forms.Button btnsua;
        private System.Windows.Forms.Button btnluu;
        private System.Windows.Forms.Button btnkluu;
        private System.Windows.Forms.Button btnthoat;
    }
}

frmSinhvien.cs
using BUS;
using DAL;
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace DE01
{
    public partial class frmSinhvien : Form
    {

        private Student sinhvien;

        public frmSinhvien()
        {
            InitializeComponent();
            sinhvien = new Student();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

            {
                 private readonly StudentModel _context;
    }
    public StudentService()
        {
            _context = new StudentModel(); // Khởi tạo context
        
    }
}   

Student.cs
namespace DAL
{
    using System;
    using System.Collections.Generic;
    using System.ComponentModel.DataAnnotations;
    using System.ComponentModel.DataAnnotations.Schema;
    using System.Data.Entity.Spatial;

    [Table("Sinhvien")]
    public partial class Student
    {
        [Key]
        [StringLength(6)]
        public string MaSV { get; set; }

        [Required]
        [StringLength(40)]
        public string HotenSV { get; set; }

        public DateTime? NgaySinh { get; set; }

        [StringLength(3)]
        public string MaLop { get; set; }

        public virtual Lop Lop { get; set; }

        public static ListView GetAll()
        {
            throw new NotImplementedException();
        }
    }

    public class ListView
    {
    }
}


StudentService.cs
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace BUS
{
    public class StudentService
    {

    }
}


StudentModel.cs
using System;
using System.ComponentModel.DataAnnotations.Schema;
using System.Data.Entity;
using System.Linq;

namespace DAL
{
    public partial class StudentModel : DbContext
    {
        public StudentModel()
            : base("name=StudentModel")
        {
        }

        public virtual DbSet<Lop> Lop { get; set; }
        public virtual DbSet<Student> Sinhvien { get; set; }
        public object Student { get; set; }

        protected override void OnModelCreating(DbModelBuilder modelBuilder)
        {
            modelBuilder.Entity<Lop>()
                .Property(e => e.MaLop)
                .IsFixedLength()
                .IsUnicode(false);

            modelBuilder.Entity<Student>()
                .Property(e => e.MaSV)
                .IsFixedLength()
                .IsUnicode(false);

            modelBuilder.Entity<Student>()
                .Property(e => e.MaLop)
                .IsFixedLength()
                .IsUnicode(false);
        }

        public static implicit operator StudentModel(Student v)
        {
            throw new NotImplementedException();
        }
    }
}


