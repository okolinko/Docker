# ************************************************************************** #
#                                                                            #
#                                                        :::      ::::::::   #
#   Dockerfile                                         :+:      :+:    :+:   #
#                                                    +:+ +:+         +:+     #
#   By: akolinko <akolinko@student.unit.ua>        +#+  +:+       +#+        #
#                                                +#+#+#+#+#+   +#+           #
#   Created: 2018/11/22 12:05:50 by akolinko          #+#    #+#             #
#   Updated: 2018/11/22 12:05:52 by akolinko         ###   ########.fr       #
#                                                                            #
# ************************************************************************** #

FROM ft-rails:on-build

EXPOSE 3000
CMD [ "rails" , "s", "-b", "0.0.0.0", "-p", "3000"]

# How to build it?
# docker build -t ex02 .

# How to run it?
# docker run -it --rm -p 3000:3000 ex02