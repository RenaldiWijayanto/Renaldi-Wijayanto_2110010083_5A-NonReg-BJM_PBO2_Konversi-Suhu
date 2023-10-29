# RenaldiWijayanto-Renaldi-Wijayanto_2110010083_5A-NonReg-BJM_PBO2_Konversi-Suhu

## Kode

Berikut adalah kode Konversi Suhu:


package konversi;

public class KonversiSuhu extends javax.swing.JFrame {

    
    public KonversiSuhu() {
        initComponents();
    }

    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        tfCelcius = new javax.swing.JTextField();
        jLabel1 = new javax.swing.JLabel();
        lblFahreinhet = new javax.swing.JLabel();
        btnConvert = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);
        setTitle("Aplikasi Konversi Suhu");

        tfCelcius.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                tfCelciusActionPerformed(evt);
            }
        });

        jLabel1.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        jLabel1.setText("Celcius");

        lblFahreinhet.setFont(new java.awt.Font("Tahoma", 0, 18)); // NOI18N
        lblFahreinhet.setText("Fahreinhet");

        btnConvert.setFont(new java.awt.Font("Tahoma", 1, 18)); // NOI18N
        btnConvert.setText("Convert");
        btnConvert.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnConvertActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(62, 62, 62)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addComponent(tfCelcius)
                    .addComponent(btnConvert, javax.swing.GroupLayout.DEFAULT_SIZE, 122, Short.MAX_VALUE))
                .addGap(56, 56, 56)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addComponent(jLabel1, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                    .addComponent(lblFahreinhet, javax.swing.GroupLayout.DEFAULT_SIZE, 89, Short.MAX_VALUE))
                .addContainerGap(162, Short.MAX_VALUE))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(71, 71, 71)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(tfCelcius, javax.swing.GroupLayout.PREFERRED_SIZE, 33, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jLabel1, javax.swing.GroupLayout.PREFERRED_SIZE, 33, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(26, 26, 26)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(btnConvert, javax.swing.GroupLayout.PREFERRED_SIZE, 40, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(lblFahreinhet, javax.swing.GroupLayout.PREFERRED_SIZE, 40, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addContainerGap(131, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                      

    private void tfCelciusActionPerformed(java.awt.event.ActionEvent evt) {                                          
        // TODO add your handling code here:
    }                                         

    private void btnConvertActionPerformed(java.awt.event.ActionEvent evt) {                                           
        // TODO add your handling code here:
        /*
        1. Ambil nilai tfCelcius masukkan ke variabel celcius
        2. Hitung dengan rumus fahreinhet = 1.8 * celcius + 32;
        3. Ubah tulisan lblfahreinhet dengan isi variabel fahreinhet
        */
        double celcius = Double.parseDouble(tfCelcius.getText());
        double fahrenheit = 1.8 * celcius + 32;
        lblFahreinhet.setText(Double.toString(fahrenheit)+"Fahrenheit");
    }                                          

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(KonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(KonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(KonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(KonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new KonversiSuhu().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton btnConvert;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel lblFahreinhet;
    private javax.swing.JTextField tfCelcius;
    // End of variables declaration                   
}



## Pembuat

Nama : Renaldi Wijayanto
NPM  : 2110010083
