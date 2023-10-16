ggplot2::theme_set(ggplot2::theme_bw() +
                     ggplot2::theme(axis.text = ggplot2::element_text(size = 18),
                                    axis.title = ggplot2::element_text(size = 15),
                                    title = ggplot2::element_text(size = 20),
                                    text = ggplot2::element_text(family = "Georgia"),
                                    strip.text = ggplot2::element_text(size = 15),
                                    legend.position = "bottom",
                                    legend.title = ggplot2::element_blank(),
                                    legend.text = ggplot2::element_text(size = 15)))


ggsave_for_presentation = function(plot_object,file_path, ...){
  
  ggsave(plot = plot_object, filename = file_path,
         device = "png",width = 33.87,
         height = 18.15,units = c("cm"),
         dpi = 300)

}
  

