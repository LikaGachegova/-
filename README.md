# -using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace эмоции
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            pictureBox1.SizeMode = PictureBoxSizeMode.Zoom;

            Image ee = Image.FromFile("Радость.PNG");
            pictureBox1.Image = ee;
        }

        private void button5_Click(object sender, EventArgs e)
        {
            pictureBox1.SizeMode = PictureBoxSizeMode.Zoom;

            Image ji = Image.FromFile("Грусть.PNG");
            pictureBox1.Image = ji;
        }

        private void button4_Click(object sender, EventArgs e)
        {
            pictureBox1.SizeMode = PictureBoxSizeMode.Zoom;

            Image fu = Image.FromFile("Смятение.PNG");
            pictureBox1.Image = fu;
        }

        private void button3_Click(object sender, EventArgs e)
        {
            pictureBox1.SizeMode = PictureBoxSizeMode.Zoom;

            Image ff = Image.FromFile("Злость.PNG");
            pictureBox1.Image = ff;
        }

        private void button2_Click(object sender, EventArgs e)
        {
            pictureBox1.SizeMode = PictureBoxSizeMode.Zoom;

            Image yo = Image.FromFile("Сигма.PNG");
            pictureBox1.Image = yo;
        }
    }
}
